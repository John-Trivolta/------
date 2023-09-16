# **Итотговый проект. Бриф "Определение уязвимых групп населения"**


## Оглавление
* [1. Описание проекта](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Описание-проекта)
* [2. Какой кейс решаем?](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Какой-кейс-решаем?)
* [3. Краткая информация о данных](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Краткая-информация-о-данных)
* [4. Этапы работы над проектом](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Этапы-работы-над-проектом)
* [5. Результат](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Результат)


### Описание проекта
Кластеризация регионов России по социальным показателям. 

:arrow_up:[к оглавлению](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Оглавление)


### Какой кейс решаем?
В России проживает большое количество людей, и многие из них находятся в тяжелых жизненных условиях. Это социальная проблема нашего государства, требующая решений федерального масштаба. Но как оказывать помощь нуждающимся гражданам централизованно? Как выявлять и решать проблему бедности и социального неблагополучия на уровне регионов России, а не локально? Каким группам населения и в каких регионах России помощь требуется в первую очередь? 
На эти вопросы нам помогут ответить модели машинного обучения, которые дают возможность кластеризовать регионы России и выделить из них наиболее остро нуждающиеся в помощи.  
Задачи:
- кластеризовать регионы России и определить, какие из них наиболее остро нуждаются в помощи бедным/уязвимым слоям населения
- описать группы населения, сталкивающиеся с бедностью
- установить есть ли влияние на уровень бедности в регионе числа детей, пенсионеров и других социально уязвимых групп
- определить, связаны ли уровень бедности/социального неблагополучия с производством и потреблением в регионе

:arrow_up:[к оглавлению](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Оглавление)


### Краткая информация о данных
- child_mortality_rural_1990_2021.xls — число умерших на первом году жизни детей за год, по всем регионам, в сельской местности.
- child_mortality_urban_1990_2021.xls — число умерших на первом году жизни детей за год, по всем регионам, в городской местности.
- disabled_total_by_age_2017_2022.csv — число людей с инвалидностью по регионам, по месяцам, по возрастным группам.
- morbidity_2005_2020_age_disease.xls — заболеваемость на 100 тыс. человек населения, по возрастным группам и группам заболеваний.
- poverty_percent_by_regions_1992_2020.csv — процент людей, живущих за чертой бедности (с денежными доходами ниже величины прожиточного минимума), оценка за год по регионам.
- welfare_expense_share_2015_2020 — расходы на социальную политику от общих расходов бюджета региона, % в год.
- cash_real_income_wages_2015_2020 — среднедушевые и реальные денежные доходы населения, номинальная и реальная начисленная зарплата, по регионам.
- poverty_socdem_20*.xls — распределение малоимущего населения по социально-демографическим группам (дети, трудящиеся, пенсионеры) за 2017–2020 гг., по регионам.
- housing_2020 — характеристика жилищных условий домохозяйств. Оценка домохозяйствами состояния занимаемого ими жилого помещения, обследование 2020 года.
- population.xlsx — численность населения по регионам и федеральным округам на 1 января каждого года за 1999–2022 гг.
- gross_regional_product_1996_2020.xls — валовой региональный продукт на душу населения, в рублях.
- regional_production_*_*.csv — объём отгруженных товаров собственного производства или работ/услуг, выполненных собственными силами, по видам деятельности за 2005–2016 гг., 2017–2020 гг. (в тысячах рублей, значение показателя за год, полный круг).
- retail_turnover_per_capita_2000_2021.xls — оборот розничной
торговли на душу населения, в рублях.
- drug_alco — сведения о заболеваемости алкоголизмом и наркоманией, на 100 тыс. населения (2005–2018).
- newborn_2006_2022_monthly.csv — рождённые в этом месяце, по регионам, без учёта мертворождённых.

:arrow_up:[к оглавлению](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Оглавление)


### Этапы работы над проектом
1. Подготовка данных
2. Анализ данных
3. Кластеризация
4. Вывод

:arrow_up:[к оглавлению](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Оглавление)


### Результат
Из проведенногом иследования можно сделать сделать следующие выводы:
- наиболее науждающимися в помощи малообеспеченным/неблагополучным
слоям населения являются регионы входящие в 0 и 2 кластеры.
- для самых неблагоприятных регионов характерны большие показатели заболеваемости алкоголизмом и наркоманией, а так же низкие заработки и большие расходы на социальную политику.
- в целом число людей с инвалидностью, детей, пенсионеров не влияет на уровень бедности, т.к. данные показатели просто коррелируют с численностью населения.
- в первую очередь на благополучие влияют показатели производства и потребления в регионе, которые абсолютно связаны с уровнем дохода населения.
- чем благополучней регион, тем меньше приходится жилой площади на одного человека.

:arrow_up:[к оглавлению](https://github.com/John-Trivolta/FINAL_PROJ/blob/master/README.md#Оглавление)
