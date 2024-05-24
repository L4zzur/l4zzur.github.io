# Полезные ссылки и материалы

## М1. Повторение
### 23 сентября 2023 (М1У2. Повторение. Функции и ООП)
[Файл со строками](m1s2.txt)


## М2. Мобильная разработка
### 30 сентября 2023 (М2У1. Введение в мобильную разработку)
[Week](https://weeek.net/ru)

[Файл с кодом](kivy/m2s1.txt)

Команда для эмуляции запуска приложения с телефона
```bash
python app.py -m screen:phone_iphone_5,portrait,scale=.5
```

### 7 октября 2023 (М2У2 Разработка MVP мобильного приложения)
Файлы с кодом 
- [main_app.py](kivy/main_app_m2s2.txt)

### 14 октября 2023 (М2У2 Разработка MVP мобильного приложения)
Файлы с кодом 
- [main_app.py](kivy/main_app_m2s2_1.txt) ```Добавлена функция check_int```
- [ruffier.py](kivy/ruffier_m2s2.txt)

### 21 октября 2023 (М2У2 Разработка MVP мобильного приложения)
Необходимые импорты для модуля `seconds.py`
```python
from kivy.uix.label import Label
from kivy.clock import Clock
from kivy.properties import BooleanProperty
```

- [main_app.py](kivy/main_app_m2s3.txt) ```Доделано использование функции check_int``` (Появится после занятия)
- [ruffier.py](kivy/ruffier_m2s2.txt) ```Без изменений```
- [seconds.py](kivy/seconds_m2s3.txt) ```Реализован класс для таймера```

### 28 октября 2023 (М2У3 От прототипа к MVP)
- [main_app.py](kivy/main_app_m2s3.txt) ```Использование функции check_int, реализация таймера на первом экране```
- [ruffier.py](kivy/ruffier_m2s2.txt) ```Без изменений```
- [seconds.py](kivy/seconds_m2s3.txt) ```Без изменений```

### 4 ноября 2023 (М2У4 Визуализация и тестирование)
Необходимые импорты для `sits.py`
```python
from kivy.uix.label import Label
```
- [main_app.py](kivy/main_app_m2s4_1.txt) ```Реализация остальных таймеров```
- [ruffier.py](kivy/ruffier_m2s2.txt) ```Без изменений```
- [seconds.py](kivy/seconds_m2s3.txt) ```Без изменений```
- [sits.py](kivy/sits_m2s4.txt) ```Реализация класса для счетчика приседаний```

### 11 ноября 2023 (М2У4 Визуализация и тестирование)
Необходимые импорты для `runner.py`
```python
from kivy.properties import NumericProperty, BooleanProperty
from kivy.uix.button import Button
from kivy.animation import Animation

from kivy.uix.boxlayout import BoxLayout
```
- [main_app.py](kivy/main_app_m2s4_1.txt) ```Реализовали анимацию для приседаний```
- [ruffier.py](kivy/ruffier_m2s2.txt) ```Без изменений```
- [seconds.py](kivy/seconds_m2s3.txt) ```Без изменений```
- [sits.py](kivy/sits_m2s4.txt) ```Без изменений```
- [runner.py](kivy/runner_m2s4.txt) ```Анимация для приседаний```

#### Эмуляция различных экранов

##### Получить список экранов
```bash
python app.py -m screen
```

##### Запустить с выбранным экраном
```bash
python app.py -m screen:phone_oneplus_6t,portrait
```

##### Список экранов
[screens.txt](kivy/screens.txt)

## М3. Анализ данных
### 18 ноября 2023 (М3У1 Анализ данных. Основы работы с Pandas. Фильтрация данных)
- [data_sience_1.py](pandas/data_sience_1.txt) 
- [data_sience_2.py](pandas/data_sience_2.txt)

### 25 ноября 2023 (М3У2 Методы группировки данных)
- [data_sience_3.py](pandas/data_sience_3.txt) 
- [data_sience_4.py](pandas/data_sience_4.txt)


### 2 декабря 2023 (М3У3 Очистка данных. Feature engineering)
- [data_cleaning.py](pandas/data_cleaning.txt) 
- [feature_engineering.py](pandas/feature_engineering.txt)


## М5. 3D-игры
### 3 февраля 2024 (М5У1 Знакомство с Panda 3D)
#### Знакомство с Panda3D
- [game.py](panda3d/lesson-1/game_test.txt)

### My Minecraft часть 1
- [game.py](panda3d/lesson-1/game.txt)
- [mapmanager.py](panda3d/lesson-1/mapmanager.txt)

### 10 февраля 2024 (М5У2 Загрузка карты. Работа с текстовыми файлами)
#### Работа с текстовыми файлами
- [file-reader.py](panda3d/lesson-2/file-reader.txt)

#### My Minecraft часть 2
Добавлена загрузка карты из внешнего txt файла
- [game.py](panda3d/lesson-2/game.txt)
- [mapmanager.py](panda3d/lesson-2/mapmanager.txt)
- [hero.py](panda3d/lesson-2/hero.txt) (пока пустой)


### 17 февраля 2024 (М5У3 Управление игроком)
#### My Minecraft часть 3.1
Добавлен объект Hero
- [game.py](panda3d/lesson-3-1/game.txt)
- [mapmanager.py](panda3d/lesson-3-1/mapmanager.txt)
- [hero.py](panda3d/lesson-3-1/hero.txt) 

### 24 февраля 2024 (М5У3 Управление игроком)
#### My Minecraft часть 3.2
- [game.py](panda3d/lesson-3-2/game.txt)
- [mapmanager.py](panda3d/lesson-3-2/mapmanager.txt)
- [hero.py](panda3d/lesson-3-2/hero.txt) 

### 2 марта 2024 (М5У4 Основной игровой режим)
#### My Minecraft часть 4.1
- [game.py](panda3d/lesson-4-1/game.txt)
- [mapmanager.py](panda3d/lesson-4-1/mapmanager.txt)
- [hero.py](panda3d/lesson-4-1/hero.txt)

### 9 марта 2024 (М5У4 Основной игровой режим)
#### My Minecraft часть 4.2
- [game.py](panda3d/lesson-4-2/game.txt)
- [mapmanager.py](panda3d/lesson-4-2/mapmanager.txt)
- [hero.py](panda3d/lesson-4-2/hero.txt)


## М6. Веб-разработка
### 16 марта 2024 (М6У1 Введение в веб-разработку)
#### Основные задания
- [task1.html](web/lesson-1/part-1/task1.txt)
- [task2.html](web/lesson-1/part-1/task2.txt)
- [task3.html](web/lesson-1/part-1/task3.txt)
- [task4.html](web/lesson-1/part-1/task4.txt)
- [task5.html](web/lesson-1/part-1/task5.txt)

#### Бонусные задания
- [task1.html](web/lesson-1/part-2/task1.txt)
- [task2.html](web/lesson-1/part-2/task2.txt)
- [task3.html](web/lesson-1/part-2/task3.txt)


### 23 марта 2024 (М6У2 Оформление веб-страниц)
#### Основы CSS
- [task1.html](web/lesson-2/task1.html.txt)
- [task2.css](web/lesson-2/task2.css.txt)
- [task3.html](web/lesson-2/task3.html.txt)
- [task3.css](web/lesson-2/task3.css.txt)
- [task4.html](web/lesson-2/task4.html.txt)
- [task4.css](web/lesson-2/task4.css.txt)
- [task5.html](web/lesson-2/task5.html.txt)
- [task5.css](web/lesson-2/task5.css.txt)

#### Flask. Запуск веб-сервера
- [index.html](web/lesson-2/flask/index.html.txt)
- [style.css](web/lesson-2/flask/style.css.txt)
- [helloworld.py](web/lesson-2/flask/helloworld.py.txt)
- [simplesite.py](web/lesson-2/flask/simplesite.py.txt)


### 30 марта 2024 (М6У3 Работа с базой данных)
#### Запросы к базе данных
- [sql_queries.py](web/lesson-3/task1/sql_queries.py.txt) `Запросы к БД`
- [Artistc.db](web/lesson-3/task1/Artistc.db) `База данных с людьми`

#### SQLite + Flask
- [helloworld.py](web/lesson-3/task2/helloworld.py.txt) `Закоментированный шаблон приложения Flask`
- [data_to_web.py](web/lesson-3/task2/data_to_web.py.txt) `Приложение Flask, выводящее людей, родившихся в запрошенный год. Для нового года нужно перезапускать приложение`
- [Artistc.db](web/lesson-3/task2/Artistc.db) `База данных с людьми`


### 6 апреля 2024 (М6У4 Структура базы данных)
#### Структура базы данных
- [db_scripts.py](web/lesson-4/db_scripts.py.txt) `Скрипты для работы с БД: очистка, создание таблиц, добавление данных`
- [quiz.py](web/lesson-4/quiz.py.txt) `пока пустой файл`
- [result.html](web/lesson-4/result.html.txt) `заготовка`
- [start.html](web/lesson-4/start.html.txt) `заготовка`
- [style_quiz.css](web/lesson-4/style_quiz.css.txt) `заготовка`
- [test.html](web/lesson-4/test.html.txt) `заготовка`


### 13 апреля 2024 (М6У4 Структура базы данных / М6У5 Динамический сайт. Сессии)
#### Структура базы данных
- [db_scripts.py](web/lesson-5-1/db_scripts.py.txt) `Добавили функцию для получения следующего вопроса`
- [quiz.py](web/lesson-4/quiz.py.txt) `пока пустой файл`
- [result.html](web/lesson-4/result.html.txt) `заготовка`
- [start.html](web/lesson-4/start.html.txt) `заготовка`
- [style_quiz.css](web/lesson-4/style_quiz.css.txt) `заготовка`
- [test.html](web/lesson-4/test.html.txt) `заготовка`

#### URL правила
- [quiz_no_session.py](web/lesson-5-1/quiz_no_session.py.txt) `заготовка с главной страницей`



### 20 апреля 2024 (М6У5 Динамический сайт. Сессии)
#### URL правила
- [quiz_no_session.py](web/lesson-5-2/quiz_no_session.py.txt) `доделанный вариант со страницей вопросов и финала, но без сессий`

#### Сессии
- [quiz.py](web/lesson-5-2/quiz.py.txt) `доделанный вариант со страницей вопросов и финала и уже с сессиями`

#### Бонусное задание. Счётчик
- [counter_global.py](web/lesson-5-2/counter_global.py.txt) `вариант счетчика с глобальной переменной`
- [counter_session.py](web/lesson-5-2/counter_session.py.txt) `вариант счетчика с сессиями`


### 27 апреля 2024 (М6У6 Получение и обработка данных)
#### HTML-формы
- [task1.html](web/lesson-6-1/task1.html.txt) `Анкета`
- [task2.html](web/lesson-6-1/task2.html.txt) `Авторизация`
- [task3.html](web/lesson-6-1/task3.html.txt) `Авиарейс`
- [task4.html](web/lesson-6-1/task4.html.txt) `Сайт`


### 4 мая 2024 (М6У6 Получение и обработка данных)
[Тестовая база данных](web/lesson-6-2/quiz.db)

#### Получение данных от пользователя
- [db_scripts.py](web/lesson-6-2/db_scripts.py.txt) `добавлены новые данные; функции для получения всех викторин, количества викторин, случайной викторины`
- [quiz.py](web/lesson-6-2/quiz.py.txt) `добавлена обработка выбора викторины пользователем`


### 11 мая 2024 (М6У7 Шаблоны)

#### Шаблоны
##### Задание 1
- [index.html](web/lesson-7-1/task1/index.html.txt)
- [sitetemplate.py](web/lesson-7-1/task1/sitetemplate.py.txt)
- [style.css](web/lesson-7-1/task1/style.css.txt)

##### Задание 2
- [index.html](web/lesson-7-1/task2/index.html.txt)
- [sitetemplate.py](web/lesson-7-1/task2/sitetemplate.py.txt)
- [style.css](web/lesson-7-1/task2/style.css.txt)


### 18 мая 2024 (М6У7 Шаблоны)

##### Файлы проекта

###### HTML
- [start.html](web/lesson-7-2/start.html.txt)
- [test.html](web/lesson-7-2/test.html.txt)
- [result.html](web/lesson-7-2/result.html.txt)
- [style_quiz.css](web/lesson-7-2/style_quiz.css.txt)
###### Python
- [db_scripts.py](web/lesson-7-2/db_scripts.py.txt)
- [quiz.py](web/lesson-7-2/quiz.py.txt)
###### База данных (заполненная)
- [quiz.db](web/lesson-7-2/quiz.db)

## AI чат-боты
[chat for ai](https://chatforai.store/)

[chkzh](https://nx.chkzh.com/)

[chatgpt usbot](https://chatgpt.usbot.net/)

### Репозитории с ссылками на другие аналоги (в большинстве случаев на китайском языке)
- [github.com/xx025/carrot](https://github.com/xx025/carrot)
- [github.com/LiLittleCat/awesome-free-chatgpt](https://github.com/LiLittleCat/awesome-free-chatgpt)
