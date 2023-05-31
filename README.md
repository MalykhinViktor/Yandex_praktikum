

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
