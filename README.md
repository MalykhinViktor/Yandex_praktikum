
# A/B-Тестирование эффективности веб-приложения

## Описание проекта:

Этот проект был проведен с целью оценки эффективности изменений, внесенных в веб-приложение. Мы провели A/B-тест, сравнив две группы пользователей (группу A и группу B), чтобы определить, какие изменения влияют на ключевые метрики производительности и пользовательского опыта.

## Выводы:

### Приоритезация гипотез:

Мы начали с приоритезации гипотез с использованием фреймворка RICE, учитывая параметр "охват". Гипотеза "Добавить форму подписки на все основные страницы, чтобы собрать базу клиентов для email-рассылок" получила наивысший приоритет из-за своего большого охвата и потенциала для увеличения числа пользователей и прибыли.

### Динамика кумулятивной выручки:

Мы обратили внимание, что начиная с 13 августа и особенно 18 августа, группа B стала значительно превосходить группу A по выручке. Это может указывать на всплески числа заказов или появление крупных заказов. Рекомендуется дополнительное исследование, чтобы выяснить причины этого изменения и убедиться, что оно не связано с выбросами данных.

### Средний чек группы B:

Средний чек в группе B в конце теста оказался значительно выше, однако он продолжает колебаться. Вероятно, это связано с наличием крупных заказов, как указывает резкий всплеск 18 августа. Нам потребуется больше данных, чтобы определить стабильность среднего чека.

### Изменения в различии между сегментами:

Мы обнаружили резкие изменения в различии между группами в нескольких точках, особенно 13 и 18 августа. Это может быть связано с крупными заказами и выбросами данных, что нужно учесть при анализе результатов.

### Поведение пользователей:

Большинство пользователей сделали не более 2 заказов, и 90% пользователей сделали только 1 заказ. Рекомендуется установить ограничение на количество заказов на одного пользователя и удалить аномальных пользователей.

### Выбросы в заказах:

Менее 5% заказов имеют стоимость выше 28000 рублей, и менее 1% - выше 58233.2 рублей. Рекомендуется удалить выбросы перед окончательным анализом данных.

### Статистическая значимость:

Анализ "сырых данных" и 'чистых данных показывает статистически значимые различия в конверсии между группами A и B, но отсутствие различий в среднем чеке. Однако после удаления выбросов, статистическая значимость различия в среднем чеке исчезает.

### Завершающее решение:

После всестороннего анализа данных и учитывая результаты, рекомендуется остановить A/B-тест и закрепить победу за группой B. Группа B продемонстрировала статистически значимое увеличение конверсии, как на "сырых данных", так и после удаления выбросов, и не оказала отрицательного влияния на средний чек.

Важно продолжать мониторинг результатов после внедрения изменений, чтобы убедиться в долгосрочной эффективности улучшений.


🏠  <a href="https://github.com/MalykhinViktor/Yandex_praktikum" target="_blank">Назад к проектам!</a>
:office:  <a href="https://github.com/MalykhinViktor" target="_blank">Назад к профилю!</a>

# A/B Testing for Web Application Effectiveness

## Project Description:

This project was conducted to assess the effectiveness of changes made to a web application. We conducted an A/B test, comparing two groups of users (Group A and Group B) to determine which changes impact key performance metrics and user experience.

## Findings:

### Hypothesis Prioritization:

We began by prioritizing hypotheses using the RICE framework, considering the "reach" parameter. The hypothesis "Add a subscription form to all main pages to collect a customer base for email newsletters" received the highest priority due to its extensive reach and potential for increasing the number of users and revenue.

### Cumulative Revenue Dynamics:

We observed that starting from August 13th, and especially on August 18th, Group B's revenue significantly surpassed that of Group A. This may indicate spikes in the number of orders or the appearance of large orders. Further investigation is recommended to determine the causes of this change and to ensure it is not related to data outliers.

### Group B's Average Check:

Group B's average check at the end of the test was significantly higher; however, it continues to fluctuate. This is likely due to the presence of large orders, as indicated by the sharp spike on August 18th. More data is needed to determine the stability of the average check.

### Changes in Segment Differences:

We found sharp changes in the differences between groups at several points, especially on August 13th and 18th. This may be associated with large orders and data outliers, which need to be considered in the analysis of results.

### User Behavior:

The majority of users made no more than 2 orders, and 90%


🏠  <a href="https://github.com/MalykhinViktor/Yandex_praktikum" target="_blank">Go back to projects</a>
:office:  <a href="https://github.com/MalykhinViktor" target="_blank"> Go back to the main profile!</a>

