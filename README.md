# Data Fusion Contest 2024 - Задача 2 «Отток»

Необходимо решить Time-to-Event задачу предсказания оттока клиентов банка на основе истории их транзакций используя данные транзакций за 6 месяцев. Особенность задачи - в рамках тренировочных данных для обучения передается не только метка, соответствующая тому, что клиент “уйдёт в отток”, но и время до его последней транзакции.

Страница с полным описанием задачи и данных для ее решения: [Data Fusion 2024 Churn](https://ods.ai/competitions/data-fusion2024-churn)

## Структура

1. [Data analysis](https://github.com/SergeiSah/DataFusion2024_ChurnModels/blob/main/Data%20analysis.ipynb) - загрузка данных их первичный анализ
2. [Features generation](https://github.com/SergeiSah/DataFusion2024_ChurnModels/blob/main/Features%20generation.ipynb) - генерация новых признаков для решения задачи
3. [Catboost](https://github.com/SergeiSah/DataFusion2024_ChurnModels/blob/main/Catboost.ipynb) - обучение модели градиентного бустинга для решения задачи
