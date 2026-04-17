## Оглавление

[1. Описание проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Описание-проекта)\
[2. Краткая информация о данных](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Краткая-информация-о-данных)\
[3. Этапы работы над проектом](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Этапы-работы-над-проектом)\
[4. Структура проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Структура-проекта)\
[5. Результат](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Результат)\
[6. Выводы](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Выводы)

### Описание проекта

В продолжении работы с датсетом из [практической задачи №1](https://github.com/senami27/Skillfactory_DST/tree/master/SF_DST/Practice-1) нобходимо посторить классификатор, который пзволит своевременно определять уходящих клиентов банка.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Оглавление)

### Краткая информация о данных

Исходный датасет представляет собой CSV файл весом 669 МБ. В нем представлены данные об оттоке клиентов некоторого банка с количеством строк 10000 в разрезе 13 признаков. Пропуски и дубликаты отсутствуют.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Оглавление)

### Этапы работы над проектом

1) Импортирование неодходимых библиотек.
2) Подгрузка данных.
3) Разведывательный анализ данных, создание дополнительных признаков, ограничение выборки.
4) Сравнительный анализ выборок.
5) Построение обучающих моделей, поиск лучших параметров и их оптимизация:
    - Построение модели логистической регрессии;
    - Построение модели логистической регрессии на полиномиальных признаках;
    - Построение модели Дерево решений;
    - Построение модели Случайный лес;
6) Предсказание вероятности ухода конкретного клиента при помощи построенных моделей обучения.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Оглавление)

### Структура проекта

[data](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/data) - папка с исходными табличными данными

[HW-3.ipynb](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/HW-3.ipynb) - jupyter-ноутбук, с кодом проекта

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Оглавление)

### Результат

В результате проекта были построены несколько моделей для предсказания оттока клиентов банка.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Оглавление)

### Выводы

В процессе выполнения кейса первоначальные данные были:

* Загружены и подготовлены;
* Проведен разведывательный анализ данных и визуализация результатов, отображающая взаимосвязи между признаками;
* Было построено несколько моделей машинного обучения для предсказания оттока клиентов;
* Было произведено предсказание ухода из банка для конкретного клиента на основе лучших моделей.

Наилучшие результаты показали модель случайного леса и модель логистической регрессии с полиномиальными коэффициентаи.

Для конкретного клиента вероятность прекратить сотрудничество была предсказана 2-мя моделями как более 60%. Скорее всего клиент уйдет. 

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-3/README.md#Оглавление)
