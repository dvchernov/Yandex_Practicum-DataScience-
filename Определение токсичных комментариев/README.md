# Определение токсичных комментариев

## Описание проекта

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

## Цель исследования

Определение токсичности комментариев.

## Ход исследования

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

## Описание данных

Столбец text в нём содержит текст комментария, а toxic — целевой признак.

## Вывод по итогам исследования
- Проведена предподготовка данных
- Тект был очищен и лематизирован
- Обучены разные модели и лучшая из них обучена на тестовой выборке
- F1 на тестовой виборке было больше 0,75
- Для поставленной задичи лучше подходит модель LogisticRegression
