# Полезные ссылки и материалы

## М1У2. Повторение. Функции и ООП.
[Файл со строками](m1s2.txt)

## М2У1. Введение в мобильную разработку.
[Week](https://weeek.net/ru)

[Файл с кодом](m2s1.txt)

Команда для эмуляции запуска приложения с телефона
```bash
python app.py -m screen:phone_iphone_5,portrait,scale=.5
```

## М2У2. Разработка MVP мобильного приложения.
### 14 октября 2023
Файлы с кодом 
- [main_app.py](kivy/main_app_m2s2.txt)

### 21 октября 2023
Файлы с кодом 
- [main_app.py](kivy/main_app_m2s2_1.txt) ```Добавлена функция check_int```
- [ruffier.py](kivy/ruffier_m2s2.txt)

### 28 октября 2023
Необходимые импорты для модуля `seconds.py`
```python
from kivy.uix.label import Label
from kivy.clock import Clock
from kivy.properties import BooleanProperty
```

- [main_app.py](kivy/main_app_m2s3.txt) ```Доделано использование функции check_int``` (Появится после занятия)
- [ruffier.py](kivy/ruffier_m2s2.txt) ```Без изменений```
- [seconds.py](kivy/seconds_m2s3.txt) ```Реализован класс для таймера```

### 4 ноября 2023
Необходимые импорты для `runner.py`
```python
from kivy.properties import NumericProperty, BooleanProperty
from kivy.uix.button import Button
from kivy.animation import Animation

from kivy.uix.boxlayout import BoxLayout
```

Необходимые импорты для `sits.py`
```python
from kivy.uix.label import Label
from kivy.clock import Clock
```

- [main_app.py](kivy/main_app_m2s3.txt) ```Использование функции check_int, реализация таймера на первом экране```
- [ruffier.py](kivy/ruffier_m2s2.txt) ```Без изменений```
- [seconds.py](kivy/seconds_m2s3.txt) ```Без изменений```
- [runner.py](kivy/runner_m2s4.txt) (Появится после занятия)
- [sits.py](kivy/sits_m2s4.txt) (Появится после занятия)


## AI чат-боты
- [Huggingface](https://huggingface.co/chat/) - первая бесплатная и открытая альтернатива ChatGPT.
- [GPTGO.ai](https://gptgo.ai/?hl=ru) - поисковая выдача с GPT.
- [smol.ai](https://smol.ai/) - **необходим вход через GitHub**, в качестве модели выбирать что-то из выделенного на скриншоте
  <img src="https://github.com/L4zzur/l4zzur.github.io/assets/66362624/0b57cac0-de0c-4bd4-a55d-4299d1137633" width="350"/>
- [geekgpt](https://chat.geekgpt.org/) - ещё альтернатива.
- [aiyunos](http://chat3.aiyunos.top) - китайская альтернатива, но должна работать аналогично.
- [eqing](https://chat.eqing.tech) - ещё одна китайская альтернатива, **необходим вход через GitHub**.
### Репозитории с ссылками на другие аналоги (в большинстве случаев на китайском языке)
- [github.com/xx025/carrot](https://github.com/xx025/carrot)
- [github.com/LiLittleCat/awesome-free-chatgpt](https://github.com/LiLittleCat/awesome-free-chatgpt)
