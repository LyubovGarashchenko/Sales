# Статистика. 
У вас есть набор данных о продажах конкретного предприятия по месяцам: [8, 15, 13, 15, 17, 20, 19, 20, 7, 14, 14, 18].

# Вам поручили написать небольшой сервис, который умеет по предоставленному ему массиву месячных продаж рассчитывать:

сумму всех продаж;
среднюю сумму продаж в месяц;
номер месяца, в котором был пик продаж, то есть осуществлены продажи на максимальную сумму*;
номер месяца, в котором был минимум продаж, то есть осуществлены продажи на минимальную сумму*;
количество месяцев, в которых продажи были ниже среднего (см. п.2);
количество месяцев, в которых продажи были выше среднего (см. п.2).

# Вам необходимо

1. Создать Maven-проект, в котором в package ru.netology.stats будет класс StatsService с необходимыми методами.
2. Написать на каждый метод по одному автотесту, который проверяет правильность работы на тестовых данных.
3. Убедиться, что ваши автотесты работают и проходят.