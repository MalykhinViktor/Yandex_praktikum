

  </a>
</div>

<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

  </a>
</div>
<img src="https://komarev.com/ghpvc/?username=MalykhinViktor&style=flat-square&color=blue" alt=""/>


<h1>
  hey there
  <img src="https://media.giphy.com/media/ymwg2hvAKuuuiDN1x3/giphy.gif" width="50px"/>
</h1>

<h2>
  My name is Viktor Malykhin
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h2>
<div align="center">
  <img src="https://media.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif" width="600" height="300"/>
</div>
Моя лента
Тесты
Курсы
Вакансии
Мероприятия

Создать запись


Подпишитесь на нас в Telegram
ОБЪЯВЛЕНИЕ
Хочешь подтянуть высшую математику для освоения Data Science?

Заходи на наш курс с преподавателями МГУ!

Подробнее
 Сергей Саляхов
17 марта 2022

18

🔥
8

💧
0

💩
1
🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
В этой статье мы создадим привлекательный профиль на GitHub: добавим гифки, эмодзи, иконки социальных сетей, GitHub-статистику, ТОП языков программирования и многое другое. Код прилагается.
1

28
🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
Статья является переводом. Оригинал доступен по ссылке.
Если вы откроете мой профиль на GitHub, вы обратите внимание на различные изображения, ссылки на социальные сети и статистику GitHub. Всё это делает профиль непохожим на остальные. Это возможно сделать с помощью файла README.md.

В этой статье мы разберём:

что такое файл README.md и как им пользоваться;
добавим информацию о себе и своих навыках;
добавим GitHub-статистику;
создадим рабочий поток GitHub для отображения постов из социальных сетей.
Чтобы всё получилось, вам нужны базовые знания HTML и Markdown.

Код из этой статьи доступен по ссылке.

Что же такое файл README.md в профиле на GitHub и для чего он нужен
Файл README.md в профиле на GitHub позволяет пользователям использовать Markdown-разметку, чтобы отображать детали о себе, о своём опыте, увлечениях, показывать GitHub-статистику и предоставлять эту информацию сообществу. Эти данные отображаются в верхней части вашей GitHub страницы над закрепленными репозиториями.

Так будем выглядеть профиль на GitHub по окончании этой статьи:

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
Мы разделим главную страницу на сектора и постепенно для каждого добавим содержимое. Цвет фона будет зависеть от цветовой темы, выбранной пользователем.

В следующем разделе мы поэтапно разберем шаги создания README-файла.

Больше полезных материалов вы найдете на нашем телеграм-канале «Библиотека программиста»
Интересно, перейти к каналу
Создание README.md на GitHub
Файл README.md находится в репозитории на GitHub, название которого совпадает с именем пользователя в вашей учетной записи. Чтобы создать репозиторий:

1. Войдите на GitHub.

2. Нажмите + в правом верхнем углу и выберите New Repository.

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
3. Откроется страница создания нового репозитория. В названии укажите имя пользователя из вашего профиля. После того как вы введете имя пользователя, будет показана информация о том, что вы создаете особый репозиторий.

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
4. Под описанием репозитория не забудьте установить отметку Public, чтобы файл README.md был виден всем.

5. Обязательно установите отметку Add a README file. Это создаст файл README.md, в котором мы и будем работать. Сравните со скриншотом, у вас должно получиться также.

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
6. Далее нажимаем кнопку Create repository. Репозиторий успешно создан. Зайдите в только что созданный репозиторий и увидите, что в нем уже есть файл README.md.

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
В следующих разделах мы добавим информацию в наш файл README.md. Мы будет работать с файлом через интерфейс GitHub, но вы можете использовать любой другой текстовый редактор.

Открываем файл README.md и вверху справа нажимаем Edit this file icon (иконка с карандашом). Также о редактировании файлов мы можем почитать в официальной документации.

Добавление GIF-изображений и значков
Ниже вы видите тот контент, который мы добавим в этой части статьи:

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
Есть множество бесплатных ресурсов, на которых вы можете взять GIF-изображения, например, для этой статьи я использовал Giphy.

Идем на страницу GIF изображения, нажимаем кнопку Share, а затем Copy GIF Link. Мы добавим эту скопированную ссылку в HTML-тег <img/>, чтобы отобразить ее в файле Markdown. Мы используем тег <img/> для упрощения настройки ширины изображения.

Замените содержимое файла README.md следующим кодом:

        
<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

    
В атрибуте src указываем ссылку, которую мы ранее скопировали. Поскольку весь контент в этой части будет выровнен по центру, мы поместили изображение в HTML-тег <div> с атрибутом align="center".

Примечание
GitHub преобразует элементы Markdown в файле README.md в HTML. После этого HTML очищается и из соображений безопасности некоторые HTML-теги игнорируются, например <script>, <style> и т. д. По этим причинам мы использовали атрибут align вместо CSS-стилей.
Перейдем в окно предпросмотра. Наша картинка появилась на странице:

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
Далее мы добавим значки для ссылок на социальные сети, при клике на которые будет открываться нужный сайт. Вы можете добавить значки для самых разных сайтов: Instagram, Facebook, Twitter и т. д. Мы добавим три значка: Twitter, YouTube и LinkedIn.

Для создания и редактирования необходимых нам значков будем использовать ресурс Shields.io. Используем URL-адрес https://img.shields.io/badge/ и передадим ему дополнительные параметры, чтобы получить нужные значки.

Первый параметр, который мы передадим, будет следующего формата: Label-Color

Здесь:

Label – название социальной сети, отображенное на значке.

Color – цвет самого значка.

Для трех социальных сетей значения будут следующие:

LinkedIn: LinkedIn-blue
Twitter: Twitter-blue
YouTube: YouTube-red
Так должен выглядеть итоговый URL для LinkedIn:

        
https://img.shields.io/badge/LinkedIn-blue

    
Если поместить этот URL в адресную строку браузера и перейти по нему, увидим следующее:

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
Обратите внимание, что пока на значке у нас только текст. Чтобы добавить логотип, нам нужно добавить в адрес еще 2 параметра:

logo = {название иконки для социальной сети}
logoColor = {цвет этой иконки}
Такой URL должен у нас получиться:

        
https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white

    
Также добавим параметр стиля к нашему URL-адресу. Существует множество вариантов стилей, подробнее можно ознакомиться на сайте Shields.io. Мы будем использовать элемент for-the-badge.

Итоговый URL для значка LinkedIn будет выглядеть так:

        
https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white&style=for-the-badge

    
Вставим этот адрес в браузер и посмотрим, что получилось:

🔥 Как креативно оформить профиль на GitHub, чтобы он привлекал внимание
По аналогии создадим URL-адреса для остальных значков:

        
https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white
https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white

    
Добавим каждый URL в тег <img/>:

        
<div id="badges">
  <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
</div>

### :man_technologist: About Me :

I'm a passionate Junior Data Analyst and Java Developer <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> from Russia
- 🏴󠁧󠁢󠁥󠁮 Foreign language proficiency - English b1, native Russian
- :seedling: Exploring Technical Content Writing.

- :zap: In my free time, I read tech articles and Surf 🏄.

- :mailbox:How to reach me: (vic.malykhin@yandex.ru)

### :hammer_and_wrench: Languages and Tools :

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/anaconda/anaconda-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/spring/spring-original-wordmark.svg" title="Spring" alt="Spring" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Flutter" alt="Flutter" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tomcat/tomcat-original.svg" title="Redux" alt="Redux " width="40" height="40"/>&nbsp;
   <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/kotlin/kotlin-original.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
   <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>

### My projects:

  -  🎵 <a href="https://github.com/MalykhinViktor/Yandex_praktikum/tree/first-project" target="_blank">Yandex Music</a>
  -  🏦  <a href="https://github.com/MalykhinViktor/Yandex_praktikum/tree/second-project" target="_blank">Investigation of the reliability of borrowers</a>
  - 🏠  <a href="https://github.com/MalykhinViktor/Yandex_praktikum/tree/third-project" target="_blank">Yandex Real Estate</a>
  - 🎦 <a href="https://github.com/MalykhinViktor/Yandex_praktikum/tree/fourth-project" target="_blank"> Research of the Russian film distribution</a>
  - 🥩 <a href="https://github.com/MalykhinViktor/Yandex_praktikum/tree/fifth-project" target="_blank">The market of public catering establishments in Moscow</a>
  -  📱 <a href="https://github.com/MalykhinViktor/Yandex_praktikum/tree/sixth-project" target="_blank"> NPS of mobile app users</a>
  -  📈 <a href="https://github.com/MalykhinViktor/Yandex_praktikum/tree/seventh-project" target="_blank"> TED Conference Research </a>

<h3>
  You can get acquainted with them in various branches of this repository
  <img src="https://media.giphy.com/media/Y01wot3Bt9Bpdz8xvs/giphy.gif" width="60px"/>
</h3>

### Courses
-  🧑‍💻<a href="https://github.com/JavaRush" target="_blank">JavaRush</a> 
-  🛢<a href="https://practicum.yandex.ru/" target="_blank">Yandex_Practicum</a> 
-  👨‍💼 IT Product Management, Suvorov IT
