<h3 align="center">Проект: "Рынок заведений общественного питания Москвы</h3>

**Описание проекта:**

Проект по анализу рынка общественного питания в Москве исследует различные аспекты заведений общепита в городе с целью помочь инвесторам из фонда "Shut Up and Take My Money" выбрать подходящее место для открытия нового заведения.

**Описание данных:**
Для проведения анализа использован датасет, составленный на основе данных сервисов Яндекс Карты и Яндекс Бизнес на лето 2022 года. Датасет содержит следующую информацию:

    id - уникальный идентификатор заведения
    object_name - название заведения
    chain - принадлежность заведения к сети (да/нет)
    object_type - тип заведения (кафе, ресторан, пиццерия и т.д.)
    address - адрес заведения
    number - количество посадочных мест в заведении
    average_bill - средний чек
    hours - часы работы заведения
    
**Шаги анализа:** 

    Загрузка и предобработка данных:
    Загрузка данных о заведениях общественного питания Москвы
    Проверка на наличие дубликатов и пропусков
    Создание столбца street с названиями улиц из столбца address
    Создание столбца is_24/7 для обозначения заведений, работающих круглосуточно
    Анализ данных:
    Исследование категорий заведений и их распределения
    Анализ количества посадочных мест в заведениях
    Исследование соотношения сетевых и несетевых заведений
    Определение популярных сетей в Москве
    Анализ административных районов Москвы, в которых расположены заведения
    Распределение средних рейтингов по категориям заведений
    Визуализация среднего рейтинга заведений по районам
    Отображение всех заведений на карте с помощью кластеров
    Идентификация топ-15 улиц по количеству заведений и их категорий
    Анализ заведений, находящихся на улицах с одним объектом общепита
    Определение ценового индикатор

**Инструменты:**

    Python, Pandas, NumPy, Matplotlib, Seaborn, PowerPoint
    
**Выводы:**

    В Москве открыто 1396 кофеен, с наибольшим количеством в Центральном административном округе.
    В Центральном административном округе и Западном административном округе есть больше круглосуточных кофеен.
    Цены на чашку кофе различаются в зависимости от района Москвы.

<h3 align="center">Project: "Moscow Public Catering Market Analysis"</h3>
**Project Description:**

The project aims to analyze the public catering market in Moscow, exploring various aspects of food establishments in the city to assist investors from the "Shut Up and Take My Money" fund in choosing a suitable location for opening a new venue.

**Data Description:**

For the analysis, a dataset compiled from Yandex Maps and Yandex Business services in the summer of 2022 was used. The dataset contains the following information:
    id - unique identifier of the establishment
    object_name - name of the establishment
    chain - affiliation of the establishment to a chain (yes/no)
    object_type - type of the establishment (cafe, restaurant, pizzeria, etc.)
    address - address of the establishment
    number - number of seats in the establishment
    average_bill - average bill
    hours - working hours of the establishment
  
 **Analysis Steps:**
 
     Data Loading and Preprocessing:
    Load data on public catering establishments in Moscow
    Check for duplicates and missing values
    Create a street column with street names extracted from the address column
    Create an is_24/7 column to indicate establishments operating 24/7
    Data Analysis:
    Explore establishment categories and their distribution
    Analyze the number of seats in the establishments
    Study the ratio of chain and non-chain establishments
    Identify popular chains in Moscow
    Analyze the administrative districts of Moscow where the establishments are located
    Distribution of average ratings by establishment categories
    Visualize the average ratings of establishments by districts
    Display all establishments on a map using clusters
    Identify the top 15 streets with the highest number of establishments and their categories
    Analyze establishments located on streets with only one food establishment
    Determine the price level indicator

**Tools Used:**


Python, Pandas, NumPy, Matplotlib, Seaborn, PowerPoint
Conclusions:

**Conclusions:**

In Moscow, there are 1396 coffee shops, with the highest number located in the Central Administrative District.
The Central Administrative District and the Western Administrative District have the most 24/7 coffee shops.
Coffee prices vary depending on the district in Moscow.


    
