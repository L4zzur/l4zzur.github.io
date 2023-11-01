# Шпаргалки и инструменты
---
 - [Как пользоваться Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637)
---
 - [Генератор кастомных бейджей](https://shields.io/)
 - [Список готовых бейджей](https://github.com/Ileriayo/markdown-badges)
 - [Сайт с гифками](https://giphy.com/)
 - [Сайт с иконками](https://www.flaticon.com/)
---
 - [Виджет с наградами пользователя](https://github.com/ryo-ma/github-profile-trophy)
 - [Статистика используемых языков](https://github.com/anuraghazra/github-readme-stats)
 - [График вашей активности на GitHub](https://github.com/Ashutosh00710/github-readme-activity-graph)
 - [Статистика вашей активности на GitHub](https://github.com/vn7n24fzkq/github-profile-summary-cards)
---
 - [Коллекция классных Readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
---
 - ### [Мой Readme](https://gist.github.com/L4zzur/b438d147a2bf8ac38e4edf7816456c18)
---
## Генераторы Readme 
 - [Генератор Readme](https://arturssmirnovs.github.io/github-profile-readme-generator/)
 - [Генератор Readme](https://profilinator.rishav.dev/)
 - [Генератор Readme](https://rahuldkjain.github.io/gh-profile-readme-generator/)
 - [Генератор Readme](https://www.profileme.dev/)
 - [Составление файла Readme](https://readme.so/ru)



# Шапка страницы
```html
<div id="header" align="center">
    	<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="100"/>
	<h1>👋Привет, я Никита</h1>
  	<h3>Python программист из Калининграда</h3>
</div>
```

Кроме того, для генерации шапки можно использовать сайт <https://reheader.glitch.me/>

![0a4f672e-7d5c-4254-8f5a-847c2924bdf6_header-image-readme-gen](https://github.com/L4zzur/l4zzur.github.io/assets/66362624/6a6e93cf-25f0-4e4e-ab26-ea077a171e84)

# Социальные сети
```html
<div id="badges">
  <a href="твоя ссылка на ВК">
      <img src="https://img.shields.io/badge/VK-blue?style=for-the-badge&logo=vk&logoColor=white" alt="VK Badge"/>
  </a>
  <a href="твоя ссылка на Telegram">
      <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="VK Badge"/>
  </a>
  <a href="твоя ссылка на Instagram">
      <img src="https://img.shields.io/badge/Instagram-purple?style=for-the-badge&logo=instagram&logoColor=white" alt="VK Badge"/>
  </a>
  // Так далее
</div>
```
Для создания и редактирования необходимых нам значков будем использовать ресурс Shields.io. Используем URL-адрес https://img.shields.io/badge/ и передадим ему дополнительные параметры, чтобы получить нужные значки.
Первый параметр, который мы передадим, будет следующего формата: `Label-Color`\
Здесь:\
`Label` – название социальной сети, отображенное на значке.\
`Color` – цвет самого значка.

Для трех социальных сетей значения будут следующие:\
VK: `VK-blue`\
Telegram: `Telegram-blue`\
YouTube: `YouTube-red`

Так должен выглядеть итоговый URL для VK:
`https://img.shields.io/badge/Telegram-blue`

Обратите внимание, что пока на значке у нас только текст. Чтобы добавить логотип, нам нужно добавить в адрес еще 2 параметра:\
`logo` = {название иконки для социальной сети}\
`logoColor` = {цвет этой иконки}

Такой URL должен у нас получиться:\
`https://img.shields.io/badge/VK-blue?logo=vk&logoColor=white`

Также добавим параметр стиля к нашему URL-адресу. Существует множество вариантов стилей, подробнее можно ознакомиться на сайте Shields.io. Мы будем использовать элемент for-the-badge.\
Итоговый URL для значка LinkedIn будет выглядеть так:\
`https://img.shields.io/badge/VK-blue?logo=vk&logoColor=white&style=for-the-badge`

# Раздел О себе

[Генератор анимированного текста с эффектом печати](https://readme-typing-svg.herokuapp.com/demo/)

Далее, добавим контент в раздел «О себе». Для оформления текста воспользуемся синтаксисом Markdown, так как нам не нужны никакие выравнивания. Добавим этот код:

`### :man_technologist: Обо мне:`
Три дефиса `---` используются для добавления горизонтальной линии перед каждым разделом. Перед и после горизонтальной линии в Markdown должны быть пустые строки.

`:woman_technologist:` используется для добавления эмодзи. Также есть мужская версия этого эмодзи `:man_technologist:`

Список эмодзи и их кодов можно найти здесь: [Список эмодзи](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

Далее мы кратко представимся. Нам будет достаточно одной строки и в этой же строке добавляем эмодзи. Вставьте следующий код в наш файл:\
`Я Python разработчик <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> из России.`

Далее напишем список фактов о себе. Для этого используем синтаксис Markdown. В начале каждой строки добавим эмодзи. Добавим следующий код и внесем соответствующие изменения.
```md   
- :telescope: Я работаю в должности инженера-программиста и вкладываюсь в разработку фронтенда и бэкенда для создания веб-приложений.
- :seedling: Изучаю техническое написание контента.
- :zap: В свободное время решаю задачи на GeeksforGeeks и читаю технические статьи.
- :mailbox: Как со мной связаться: [![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat&logo=gmail&logoColor=white)](mailto:ТВОЯ ПОЧТА)
```
Обрати внимание на последнюю строку. Внутри мы использовали элементы синтаксиса Markdown ![]() чтобы отобразить значок Gmail.

# Раздел Языки и инструменты
Заголовок раздела
`### :hammer_and_wrench: Языки и инструменты:`

[Simple Icons](https://github.com/simple-icons/simple-icons) — огромная коллекция иконок популярных брендов, компаний, технологий и сервисов в svg-формате. У проекта есть сайт, на котором можно найти удобную иконку и скачать себе, а потом использовать в своем md-файле. Вставлять изображения лучше с помощью HTML — так удобнее задавать необходимый размер.
![image](https://github.com/L4zzur/l4zzur.github.io/assets/66362624/80dc5d17-3fba-4cda-aace-b2d6eacc4ba9)

Вставка изображений с помощью html


[Markdown Badges](https://github.com/Ileriayo/markdown-badges) — библиотека бейджей с готовыми фрагментами md-кодов для вставки. Коллекция обширная, можно найти необходимые языки программирования, технологии и оформить блок, к примеру, навыков.
![image](https://github.com/L4zzur/l4zzur.github.io/assets/66362624/482137e9-1be2-48e3-9115-7062f88aa337)



# Статистика
В README-файл профиля можно добавлять различные виджеты со статистическими данными о себе и свой деятельности на GitHub. Данные автоматически обновляются с некоторой периодичностью и в профиле всегда отображается актуальная информация:

[GitHub Trophy](https://github.com/ryo-ma/github-profile-trophy) — добавляет в профиль трофеи и ачивки. Награды показывают, насколько пользователь активно ведет свой профиль. Для выбора доступно более десяти различных цветовых схем, что позволяет настроить виджет под свой стиль оформления. Также можно выбрать различные варианты расположения наград и включить фильтрацию. Для добавления необходимо вставить следующий md-код в свой файл, параметр username= необходимо заменить на свой никнейм на платформе.

`[![trophy](https://github-profile-trophy.vercel.app/?username=ТВОЙ НИКНЕЙМ)](https://github.com/ryo-ma/github-profile-trophy)`\
[trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma)

[Longest streak stats](https://github.com/DenverCoder1/github-readme-streak-stats) — добавляет виджет, показывающий актуальную продолжительность ежедневных сессий на GitHub, самую длинную сессию за все время и суммарное количество вкладов в сообщество. Автор виджета предлагает подробную инструкцию по его настройке, но вместе с этим предоставляет и визуальный конструктор, позволяющий настроить необходимую цветовую схему. Кроме этого, в репозитории разработчика имеется руководство по развертыванию приложения на собственном сервере. Если вставлять код из примеров, то параметр user= надо заменить на свой никнейм, если создавать собственный дизайн в конструкторе, то система выдаст необходимый код для вставки.
[Конструктор](https://github-readme-streak-stats.herokuapp.com/demo/)

`[GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ТВОЙ НИКНЕЙМ)`\
[GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=L4zzur)

[Top Languages Card](https://github.com/anuraghazra/github-readme-stats) — виджет, выводящий статистику по часто используемым языкам в репозиториях пользователя. Можно выводить информацию как по всем репозиториям в профиле, так и только по избранным. Есть возможность удалить некоторые языки и никогда не показывать их в поле активности. Также можно выбрать компактный и более подробный вид карточки. Есть поддержка разных цветовых схем. При вставке кода необходимо заменить параметр username= на свой никнейм.

<!---Для компактной версии-->
`[Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ТВОЙ НИКНЕЙМ&layout=compact)`\
[Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)

<!---Для подробной версии-->
`[Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ТВОЙ НИКНЕЙМ)`\
[Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)

[GitHub Stats Card](https://github.com/anuraghazra/github-readme-stats) — карточка от разработчика прошлого виджета. Виджет выводит основную информацию о деятельности пользователь на платформе — общее количество звезд, коммитов и вкладов в сообщество. Также карточка отображает оценку пользователя, сравнивая его деятельность с другими юзерами GitHub. Доступно около десятка уже готовых тем, но можно настроить и уникальную. Ненужные позиции в статистике можно скрыть. Для вставки все так же надо скопировать код, добавить в свой файл и заменить параметр username= на актуальный.

`[Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)`\
[Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

[GitHub Profile Views Counter](https://github.com/topics/visitor-counter) — небольшой бейдж, выводящий информацию о количестве посетителей профиля. В поиске GitHub можно найти несколько репозиториев с реализацией виджета, но устроены они приблизительно одинаково, поэтому рассмотрим на примере самого популярного. Бейдж можно персонализировать, выбрав цвет из готовых или указать необходимый в шестнадцатеричной системе, на выбор есть три разных дизайна и возможность изменить исходный текст бейджа. Для вставки надо заменить поле your-github-username на соответствующее своему никнейму.

`![](https://komarev.com/ghpvc/?username=ТВОЙ НИКНЕЙМ)`\
![](https://komarev.com/ghpvc/?username=L4zzur)


Забавы ради
В readme-файлы профиля можно добавлять не только полезные статистические данные, но и различные украшения и забавные блоки. Эти элементы не расскажут о пользователе как о специалисте, но могут пригодиться для оформления.

[README Jokes](https://github.com/ABSphreak/readme-jokes) — карточки со случайно генерируемыми шутками. В репозитории есть пара десятков готовых тем, но доступна и кастомизация, поэтому можно воплотить практически любое цветовое решение. Для вставки в профиль надо просто скопировать себе следующий фрагмент кода.

Markdown:

`![Jokes Card](https://readme-jokes.vercel.app/api)`\
![Jokes Card](https://readme-jokes.vercel.app/api)

[Github Readme Quotes](https://github.com/PiyushSuthar/github-readme-quotes) — динамически выводит блок с цитатами. Размер ограничен двумя вариантами — вертикальный и горизонтальный, а цветовых схем четыре. В будущем автор проекта планирует расширить параметры кастомизации. Встроить в свой профиль можно с помощью следующего md-кода:

`[Readme Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)`\
[Readme Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)
