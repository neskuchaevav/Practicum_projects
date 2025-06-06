# Проект: Машинное обучение в бизнесе

Для нефтедобыващей компании необходимо рассчитать и определить локацию для разработки месторождения и бурения нефтянных скважин.
Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. В проекте необходимо построить модель для определения региона, где добыча принесёт наибольшую прибыль и проанализировать возможную прибыль и риски техникой Bootstrap.

## Основные библиотеки:
- pandas
- numpy
- scipy
- seaborn
- matplotlib
- sklearn

## Краткое описание работ
- В проекте выполненны исследования характеристик качества нефти и объёмов её запасовпо для 10 000 скважин по предоставленным данным для трех регионов.
- Построена и обучена линейной регрессии для предсказания объема запасов в новых скважинах.
- По результатам моделирования выбраны 200 скважин с самыми высокими оценками значений.
- Применена технология bootstrap с разделением каждого предсказанного значения прибыли по регионам на 1000 выборок.