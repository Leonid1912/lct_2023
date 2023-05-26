# LTC 2023

## Команда __CIBAA__



ЗАДАЧА №15

## Чем мы занимались 

Мы разделини задачу на две подзадачи, обучение модели и подготовка файла и интерфейс для отслеживания неисправносей.

### Предсказание неисправностей

Для решения задачи мы попробвали три разных подхода по двум направлениям:

- предсказание временных рядов на основе агрегатов по историческим данным
    > тут мы сделали два предположения 
    - обучать модель на каждом эксгуастере отдельно
    - обучать модель на всех эксгуастерах

- предсказание временных рядов на основе аддитивной модели (мы использовали `prophet`)


### Интерфейс для отслеживания неисправностей

Вторая часть задачи, интерфейс для отслеживания неисправностей. 

По второй задаче мы реализовали web-приложение `Monitor`. Подробнее о нем написано в README его репозитория.




