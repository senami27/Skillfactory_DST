## Оглавление

[1. Описание проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Описание-проекта)\
[2. Краткая информация о данных](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Краткая-информация-о-данных)\
[3. Этапы работы над проектом](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Этапы-работы-над-проектом)\
[4. Структура проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Структура-проекта)\
[5. Результат](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Результат)\
[6. Выводы](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Выводы)

### Описание проекта

Необходимо предсказать биологический ответ молекул (столбец 'Activity') по их химическому составу.

Необходимо обучить две модели: логистическую регрессию и случайный лес. Далее нужно сделать подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации. Важно использовать все четыре метода (GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna) хотя бы по разу, максимальное количество итераций не должно превышать 50.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Оглавление)

### Краткая информация о данных

Исходный датасет представляет собой csv файл весом 18187 КБ. Количество строк - 3751, столбцов - 1777. Тип данных float64, int64. 

Каждая строка представляет молекулу. Первый столбец Activity содержит экспериментальные данные, описывающие фактический биологический ответ [0, 1]; Остальные столбцы D1-D1776 представляют собой молекулярные дескрипторы — это вычисляемые свойства, которые могут фиксировать некоторые характеристики молекулы, например размер, форму или состав элементов.

Предварительная обработка не требуется, данные уже закодированы и нормализованы.

Оригинальный датасет: [Predicting a Biological Response (kaggle.com)](https://www.kaggle.com/c/bioresponse)

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Оглавление)

### Этапы работы над проектом

1) Импортирование неодходимых библиотек.
3) Подгрузка данных.
4) Обучение 2-х моделей (логистическая регрессия и модель случайного леса) с параметрами по умолчанию (Baseline).
5) Подбор гиперпараметров для каждой из моделей 4-мя способами (GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna) с обучением на кросс-валидации.
6) Сравнение моделей на основании полученных метрик и выбор оптимальной.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Оглавление)

### Структура проекта

[data](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/data) - папка с исходными табличными данными

[HW-5.ipynb](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/HW-5.ipynb) - jupyter-ноутбук, с кодом проекта

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Оглавление)

### Результат

Было обучено 2 модели с оптимизацией гиперпараметров на кросс-валидачии.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Оглавление)

### Выводы

В процессе выполнения кейса:

* Данные были загружены и подготовлены;
* Были построены модели логистической регрессии и случайного леса с параметрами по умолчанию;
* Были подобраны гиперпараметры для каждой из моделей 4-мя способами;

Наилучшее сочетание по метрикам у модели RandomForestClassifier с Optuna. 

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-5/README.md#Оглавление)
