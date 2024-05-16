from flask import Flask, redirect, url_for, session, request
from db_scripts import get_next_question, get_quizes, get_quiz_count, get_random_quiz_id


def start_quiz(quiz_id):
    session["quiz"] = quiz_id
    session["last_question"] = 0

def get_form_quizes():
    form_str = '''
    <form method="post" action="/">
    <select name="quiz">
    '''

    quiz_list = get_quizes()
    for id, name, min_age, max_age in quiz_list:
        option = f'<option value="{id}">{name}</option>'
        form_str += option
    
    form_str += '''
    </select>
    <p><input type="submit" value="Выбрать"></p>
    </form>
    '''
    return form_str


def index():
    if request.method == "GET":
        start_quiz(-1)
        html = '<html><body><h2>Выберите викторину:</h2>'
        html += get_form_quizes()
        html += '</body></html>'
        return html
    elif request.method == "POST":
        quiz_id = request.form.get("quiz")
        start_quiz(quiz_id)
        return redirect(url_for("test"))


def test():
    if "quiz" in session and int(session["quiz"]) >= 0:
        question = get_next_question(session["last_question"], session["quiz"])
        if question is None or len(question) == 0:
            return redirect(url_for("result"))
        else:
            session["last_question"] = question[0]
            return f"<h1>{session["quiz"]}</h1><h2>{question}</h2>"
    else:
        return redirect(url_for("index"))


def result():
    return "<h1>That's all folks!</h1>"


app = Flask(__name__)
app.config["SECRET_KEY"] = "ThisIsSuperSecretKey"
app.add_url_rule("/", "index", index, methods=["GET", "POST"])
app.add_url_rule("/test", "test", test)
app.add_url_rule("/result", "result", result)
# 127.0.0.1:5000

if __name__ == "__main__":
    app.run()
