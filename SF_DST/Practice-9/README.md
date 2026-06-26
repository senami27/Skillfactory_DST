## Оглавление

[1. Описание проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Описание-проекта)\
[2. Краткая информация о данных](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Краткая-информация-о-данных)\
[3. Этапы работы над проектом](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Этапы-работы-над-проектом)\
[4. Структура проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Структура-проекта)\
[5. Результат](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Результат)\
[6. Выводы](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Выводы)

### Описание проекта

Необходимо реализовать координатный спуск, стохастический градиентный спуск, оценить качество обеих полученных моделей с помощью MSE и MAE, и проинтерпретировать результаты работы.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Оглавление)

### Краткая информация о данных

Исходный датасет представляет собой csv файл весом 5 КБ. Количество строк - 200, столбцов - 5. Тип данных float64, int64. В данных дубликаты и пропуски отсутствуют.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Оглавление)

### Этапы работы над проектом

1) Импортирование неодходимых библиотек.
3) Подгрузка и подготовка данных.
4) Реализация алгоритма координатного спуска.
5) Реализация стахостического градиентного спуска:
   - масштабирование столбцов исходой таблицы;
   - создание функции для вычисления среднеквадратической ошибки;
   - составление наивного прогноза (среднее значение);
   - создание функции для получения вектора прогнозов;
   - создание функции для реализации шага стахостического градиентного спуска;
   - создание функции для реализации стахостического градиентного спуска;
8) Оценка качества обеих полученных моделей с помощью MSE и MAE.
9) Выводы по проекту.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Оглавление)

### Структура проекта

[data](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/data) - папка с исходными табличными данными

[HW-8.ipynb](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/HW-8.ipynb) - jupyter-ноутбук, с кодом проекта

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Оглавление)

### Результат

Были реализованы функции координатного и градиентного спусков и проведена оценка их с помощью MSE, MAE.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Оглавление)

### Выводы

В процессе выполнения задачи:
- Данные были загружены, проанализированы и подготовлены к построению моделей;
- Реализованы функции координатного и градиентного спусков;
- Проведена оценка качества моделей;

Оба алгоритма сошлись на одном уровне (метрика MSE), но в разных точках пространства (разные вектора весов).

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-8/README.md#Оглавление)
