# time-series-2
Данные - 'mean-monthly-air-temperature-deg.csv'

Задача 1. Получить стационарный ряд.

Над оригинальным рядом проведены операции:
1. Логарифмирование
2. Дифференцирование с лагом = 1 (для устранения тренда)
3. Дифференцирование с лагом = 1 (для устранения сезонности)

Тест Dickey-Fuller показал у полученного ряда p-value = 2.361163522472863e-12
Тест Shapiro-Wilk на нормальность распределения показал p-value = 0.2528594732284546

Задача 2. Приблизить оба ряда моделями из класса MA.



Задача 3. Оценить качество.
