# ML для текстов
--------------------------------------------------------------------------------------------------------------------------------
### Цель

Интернет-магазин запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Требуется инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

--------------------------------------------------------------------------------------------------------------------------------
### Вывод

Для определения тональности текста были обучены модели RandomForestClassifier,LGBMClassifier, LogisticRegression. F1 мера при тестировании модели RandomForestClassifier равна 0.92, что выше минимального значения, которое требовалось по условиям проекта

--------------------------------------------------------------------------------------------------------------------------------
### Стек технологий: NLP, Pandas, Sklearn, Pytorch, BERT, LogisticRegression, LGBMClassifier, RandomForestClassifier, GridSearchCV, RandomizedSearchCV
--------------------------------------------------------------------------------------------------------------------------------
### Статус проекта

Завершен.

--------------------------------------------------------------------------------------------------------------------------------
