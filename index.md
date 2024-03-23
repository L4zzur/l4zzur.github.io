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
#### Интернет


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
