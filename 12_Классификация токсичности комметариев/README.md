# Классификация комментариев.

## Задача пректа.
Ускорить модерацию комментариев в сообществе, автоматизировав оценку их токсичности.
Обучить модель классифицировать комментарии на позитивные и негативные.

## Описание работы.
Для запуска нового сервиса интернет-магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. 
- Обучена модель классифицировать комментарии на позитивные и негативные.
- Проанализирован набор данных с разметкой о токсичности правок.

## Результат.
Построена модель со значением метрики качества F1 не меньше 0.75.
К текстам и временным рядам применена техника feature engineering. 
Векторизированы тексты посредством word2vec, GloVe, FastText.