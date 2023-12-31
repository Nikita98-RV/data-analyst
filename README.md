# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут ``Никита Ребров``, я начинающий аналитик данных. 
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``


## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:<p>
<ol>
<li>Задача №1 - Добавить в калькулятор поправочный коэффициент и с его помощью пересчитать количество студентов.</li>
<li>Задача №2 - Пересчитать план найма преподавателей с учетом новых данных, изменив значения пропускной способности и ретеншена преподавателей.</li>
</ol>

<p>Как решил:<p>
<ol>
<li> №1: Добавил в список показатель "Поправочный коэф-т на привлечение". Настроил динамический расчёт. Просчитал сценарий, при котором планы маркетинга будут увеличены на 12%.</li>
<li> №2: Просчитал сценарий, при котором Пропускная способность П увеличится на 15 процентов, а Retention П упадёт на 2 процента. С помощью Поиска решений составил новый план найма с ограничением: за месяц нельзя нанять более 70 преподавателей</li>
</ol>

> <a href="https://github.com/Nikita98-RV/data-analyst/blob/main/folder/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%E2%84%961%20%D0%9A%D0%B0%D0%BB%D1%8C%D0%BA%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80.png" >Ссылка на проект</a>  
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1 - Обновленный лист с калькулятором + новое количество студентов.</li>
  <li>Итог №2 - Обновленный план по найму с количеством новых преподавателей по месяцам.</li>
</ol>
<br> 

<p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1 - Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.</li>
  <li>Задача №2 - Сколько самых популярных фильмов нужно взять, чтобы покрыть половину всех просмотров? </li>
  <li>Задача №3 - Есть ли разница между активностью в выходные дни и в будние? </li>
  <li>Задача №4 - Как распределены пользователи по часовым поясам? </li>
</ol>

<p>Как решил: <p>

> <a href="https://github.com/Nikita98-RV/data-analyst/tree/main/folder/%D0%BF%D0%BE%D1%80%D0%B5%D0%BA%D1%82%202">Ссылка на проект</a>
 
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1 - Чтобы повысить маржинальность на 25% нам нужно увеличить Retention до 90%, увеличить стоимость подписки до 400р и убрать скидки, уменьшить затраты на маркетинг на 30%, и на 22% расходы. </li>
  <li>Итог №2 - Достаточно первых 73 фильма чотбы покрыть 50% просмотров. </li>
  <li>Итог №3 - В среднем, в выходные на 20% активность больше чем в будни. </li>
  <li>Итог №4 - Большинство поьзователей (80%) зарегестрированы в 4 поясах: UTC+0; UTC+1; UTC+2; UTC+3. А половина пользователей (51%) в 2 поясах: UTC+1; UTC+2. </li>
</ol>
<br> 
<p> Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</p>
<p>Что нужно было сделать:<p>
<ol>
   <li>Задача №1 - Рассмотреть только первые покупки для каждого клиента: постройте распределение количества первых покупок клиента.</li>
   <li>Задача №2 - Построить винтажные доходимости, т. е. для каждого партнера необходимо рассчитать, какой процент клиентов дошел до второй покупки, до третьей покупки и т. д.</li> 
</ol>
<p>Как решил: <p>
<ol>
<li> №1: Воспользовался row_number() проставил ранги покупок в рамках каждого клиента по времени. Сгруппировал полученные результаты, нашел количество строк для каждого значения.</li>
<li> №2: Воспользовался конструкцией case when, чтобы найти количество дошедших до каждой покупки. Чтобы найти, какой процент дошел до определенной покупки поделил количество вторых на количество первых и т.д. </li>
</ol>

> <a href="https://drive.google.com/drive/folders/1rSy-lz1OubofT4Tj7vijScpGeQYj9de8">Ссылка на проект</a>  
<br> 

