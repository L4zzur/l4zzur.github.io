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
```
Module usage: python main.py -m screen:deviceid[,orientation]

Available devices:

Device ID    Name                   Width    Height   DPI   Density
onex         HTC One X              1280     720      312   2
one          HTC One                1920     1080     468   3
onesv        HTC One SV             800      480      216   1.5
s3           Galaxy SIII            1280     720      306   2
note2        Galaxy Note II         1280     720      267   2
droid2       Motorola Droid 2       854      480      240   1.5
xoom         Motorola Xoom          1280     800      149   1
ipad         iPad (1 and 2)         1024     768      132   1
ipad3        iPad 3                 2048     1536     264   2
iphone4      iPhone 4               960      640      326   2
iphone5      iPhone 5               1136     640      326   2
xperiae      Xperia E               480      320      166   1
nexus4       Nexus 4                1280     768      320   2
nexus7       Nexus 7 (2012 version) 1280     800      216   1.325   
nexus7.2     Nexus 7 (2013 version) 1920     1200     323   2
phone_android_one Android One            854      480      218   1.5
phone_htc_one_m8 HTC One M8             1920     1080     432   3.0
phone_htc_one_m9 HTC One M9             1920     1080     432   3.0
phone_iphone iPhone                 480      320      168   1.0
phone_iphone_4 iPhone 4               960      640      320   2.0
phone_iphone_5 iPhone 5               1136     640      320   2.0
phone_iphone_6 iPhone 6               1334     750      326   2.0
phone_iphone_6_plus iPhone 6 Plus          1920     1080     400   3.0
phone_lg_g2  LG G2                  1920     1080     432   3.0
phone_lg_g3  LG G3                  2560     1440     533   3.0
phone_moto_g Moto G                 1280     720      327   2.0
phone_moto_x Moto X                 1280     720      313   2.0
phone_moto_x_2nd_gen Moto X 2nd Gen         1920     1080     432   3.0
phone_nexus_4 Nexus 4                1280     768      240   2.0
phone_nexus_5 Nexus 5                1920     1080     450   3.0
phone_nexus_5x Nexus 5X               1920     1080     432   2.6
phone_nexus_6 Nexus 6                2560     1440     496   3.5
phone_nexus_6p Nexus 6P               2560     1440     514   3.5
phone_oneplus_3t OnePlus 3t             1863     1080     380   2.375
phone_oneplus_6t OnePlus 6t             2340     1080     420   2.625
phone_samsung_galaxy_note_4 Samsung Galaxy Note 4  2560     1440     514   3.0
phone_samsung_galaxy_s5 Samsung Galaxy S5      1920     1080     372   3.0
phone_samsung_galaxy_s6 Samsung Galaxy S6      2560     1440     576   4.0
phone_sony_xperia_c4 Sony Xperia C4         1920     1080     400   2.0
phone_sony_xperia_z_ultra Sony Xperia Z Ultra    1920     1080     348   2.0
phone_sony_xperia_z1_compact Sony Xperia Z1 Compact 1280     720      342   2.0
phone_sony_xperia_z2z3 Sony Xperia Z2/Z3      1920     1080     432   3.0
phone_sony_xperia_z3_compact Sony Xperia Z3 Compact 1280     720      313   2.0
tablet_dell_venue_8 Dell Venue 8           2560     1600     355   2.0
tablet_ipad  iPad                   1024     768      132   1.0
tablet_ipad_mini iPad Mini              1024     768      163   1.0
tablet_ipad_mini_retina iPad Mini Retina       2048     1536     326   2.0
tablet_ipad_pro iPad Pro               2732     2048     265   2.0
tablet_ipad_retina iPad Retina            2048     1536     264   2.0
tablet_nexus_10 Nexus 10               2560     1600     297   2.0
tablet_nexus_7_12 Nexus 7 12             1280     800      216   1.3
tablet_nexus_7_13 Nexus 7 13             1920     1200     324   2.0
tablet_nexus_9 Nexus 9                2048     1536     288   2.0
tablet_samsung_galaxy_tab_10 Samsung Galaxy Tab 10  1280     800      148   1.0     
tablet_sony_xperia_z3_tablet Sony Xperia Z3 Tablet  1920     1200     282   2.0
tablet_sony_xperia_z4_tablet Sony Xperia Z4 Tablet  2560     1600     297   2.0
tablet_huawei_mediapad_m3_lite_10 HUAWEI MediaPad M3 Lite 10 1920     1200     320   2.25


Simulate a medium-density screen such as Motorola Droid 2:

    python main.py -m screen:droid2

Simulate a high-density screen such as HTC One X, in portrait:

    python main.py -m screen:onex,portrait

Simulate the iPad 2 screen

    python main.py -m screen:ipad

If the generated window is too large, you can specify a scale:

    python main.py -m screen:note2,portrait,scale=.75
```


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
