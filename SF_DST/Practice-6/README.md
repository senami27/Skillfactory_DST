## Оглавление

[1. Описание проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Описание-проекта)\
[2. Краткая информация о данных](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Краткая-информация-о-данных)\
[3. Этапы работы над проектом](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Этапы-работы-над-проектом)\
[4. Структура проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Структура-проекта)\
[5. Результат](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Результат)\
[6. Выводы](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Выводы)

### Описание проекта

Необходимо решить задачу кластеризации покупателей некоторой продуктовой фирмы. Для этого снизим размерность данных с помощью PCA и оценим количество кластеров, качество полученной модели кластеризации на основе k-means и сделаем финальный портрет покупателя из каждой группы.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Оглавление)

### Краткая информация о данных

Исходный датасет представляет собой csv файл весом 216 КБ. Количество строк - 2240, столбцов - 29. Тип данных float64, int64, object. В данных есть пропуски, необходима базовая предобработка и создание нужных признаков.

В датасете представлены персональные данные покупателей, такие как состав семьи, доход, вовлеченность в маркетинговые кампании, интересы по разным категориям товаров.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Оглавление)

### Этапы работы над проектом

1) Импортирование неодходимых библиотек.
3) Подгрузка и первичная бработка данных (удаление пропусков, изменение типов, создание признаков, работа с выбросами).
4) Корреляционный анализ численных признаков.
5) Кодировкание признаков с помощью  LabelEncoder и стандартизация.
6) Снижение размерности (PCA).
7) Построение модели кластеризации (k-means) с определнием оптимального кол-ва кластеров с Elbow Method.
8) Анализ результатов кластеризации и выводы.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Оглавление)

### Структура проекта

[data](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/data) - папка с исходными табличными данными

[HW-6.ipynb](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/HW-6.ipynb) - jupyter-ноутбук, с кодом проекта

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Оглавление)

### Результат

Был проведен анализ и подготовка данных, снижена размерность с помощью PCA, построена модель кластеризации k-means.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Оглавление)

### Выводы

В процессе выполнения кейса:

* Данные были загружены и подготовлены;
* Была снижена размерность данных с помощью PCA.
* Построена модель кластеризации k-means;

Разбиение кластеров приблиительно равно, наибольшие траты характерны для группы, где больше заработок. 

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-6/README.md#Оглавление)
