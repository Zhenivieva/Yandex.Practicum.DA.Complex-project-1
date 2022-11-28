# Yandex.Practicum.DA.Complex-project-1
Yandex Practicum. Data-analyst course. С8 Сборный проект-1 Проверка гипотез о выручке сотового оператора.   
Спринт 8 Сборный проект -1
## Сборный проект -1 Проверка гипотез о выручке сотового оператора

**Описание проекта**   
В нашем распоряжении исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы до 2016 г. Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. Нужно отработать принцип работы с данными для прогноза продаж последующих годов по данным предшествующих. В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».  
**Цель исследования**  
Выявить определяющие успешность игры закономерности.    
**Ход исследования**   
Исторические данные о продажах игр получим из файла games.csv. О качестве данных ничего неизвестно. Поэтому перед проведением анализа и проверкой гипотез понадобится обзор и предобработка данных. Обработаем пропуски, исправим названия и типы данных в столбцах,удалим дубликаты в данных, а также редкие и выбивающиеся значения.    
Таким образом, исследование пройдёт в пять этапов:  
1. Обзор данных.
2. Предобработка данных:  
-Названия столбцов  
-Обработка пропусков, температурный график по количеству пропусков,
заполнение пропусков  
-Преобразование типов данных в столбцах  
-Поиск и удаление дубликатов  
-Аномалии в данных  
3. Исследовательский анализ данных  
-Изучим, сколько игр выпускалось в разные годы  
-Посмотрим, как менялись продажи по платформам  
-Проанализируем данные по продажам игр разных платформ за актуальный период  
-Построим график «ящик с усами» по глобальным продажам игр в разбивке по платформам  
-Посмотрим, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков (диаграммы рассеяния с линией регрессии, коэффициент Пирсона)  
-Исследуем распределение игр по жанрам (динамика продаж игр разных жанров по годам)  
4. Составление портрета пользователя каждого региона
Проведя исследование ТОП-5 самых популярных платформ и жанров для каждого региона , а также оценив влияние рейтинга ESRB на продажи в отдельном регионе, можем составить портрет пользователя каждого региона (сводные графики, subplot)  
5. Проверка гипотез  
-Проверка гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые (Нулевая гипотеза, альтернативная гипотеза, p-value)  
-Проверка гипотезы: cредние пользовательские рейтинги жанров Action и Sports разные (Нулевая гипотеза, альтернативная гипотеза, p-value)
