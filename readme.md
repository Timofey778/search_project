# Поиск в миниатюре

Проект представляет собой постепенное построение маленького поисковика со следующей архитектурой:

* по документам строится инвертированный индекс и индекс фичей;
* по запросу из индекса вынимается список кандидатов;
* список кандидатов ранжируется по релевантности с помощью GBDT по индексу фичей.


## Задания

1. Имплементировать инвертированный индекс.
2. Научиться генерировать список кандидатов и минимально его ранжировать.
3. Настроить процесс feature extraction для документов.
4. Обучить GBDT для ранжирования кандидатов.
5. Отранжировать выдачу полученным GBDT.

6. ****Улучшать качество, улучшать первичную фильтрацию, ускорять поиск.****