# Проект для «Викишоп»

## Описание проекта
Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 

Обучим модель классифицировать комментарии на позитивные и негативные. В нашем распоряжении набор данных с разметкой о токсичности правок.

Построим модель со значением метрики качества *F1* не меньше 0.75. 

## План работы

1.	Загрузим и подготовим данные.
2.	Обучим разные модели.
3.	Сделаем выводы.

Для выполнения проекта применять *BERT* необязательно.

## Описание данных

-	`text` — содержит текст комментария

Целевой признак:
-    `toxic`

Данные находятся в файле: `toxic_comments.csv` 
