## Рекомендация тарифов
Многие клиенты оператора мобильной связи «Мегалайн» пользуются архивными тарифами. Компания планирует построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

Есть данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных уже проведена.

Необходимо построить модель с максимально большим значением accuracy, не менее 0,75.

### Описание данных

Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. 
Известно:

- сalls — количество звонков
- minutes — суммарная длительность звонков в минутах
- messages — количество sms-сообщений
- mb_used — израсходованный интернет-трафик в Мб
- is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0)

### План проекта

1. Исходные данные, общая информация
2. Выделение трех выборок
3. Исследование модели
4. Оценка моделей на тестовой выборке
5. Проверка моделей на адекватность<br>
Заключение
