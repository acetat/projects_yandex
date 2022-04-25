# Описание проекта: Отток клиентов банка

## Данные

В наличии были данные о клиентах (пол, местоположение, уровень зарплаты итд)

## Задача

Анализ оттока клиентов из банка для выбора стратегии (удержание старых клиентов или привлечение новых клиентов).

## Результаты 
- Спрогнозирована вероятность ухода клиента из банка в ближайшее время.
- Построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке. Метрика доведена до 0.64. 
- Дополнительно измерен AUC-ROC, соотнесен с F1-мерой.

## Используемые библиотеки
*pandas, Matplotlib, numpy, SciPy*