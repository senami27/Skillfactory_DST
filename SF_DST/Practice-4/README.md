## Оглавление

[1. Описание проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Описание-проекта)\
[2. Краткая информация о данных](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Краткая-информация-о-данных)\
[3. Этапы работы над проектом](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Этапы-работы-над-проектом)\
[4. Структура проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Структура-проекта)\
[5. Результат](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Результат)\
[6. Выводы](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Выводы)

### Описание проекта

Необходимо обучить модель линейной регрессии на отобранных 3-х признаках и сравнить полученные результаты.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Оглавление)

### Краткая информация о данных

Исходный датасет представляет собой xlsx файл весом 495 КБ. В нем представлены данные с количеством строк более 7000 в разрезе 12 признаков типа object, float64, int64, иеются пропуски. В связи с этим необходимо подготовить данные к работе: удалить пропуски, преобразовать признаки, выделить только нужные данные для работы.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Оглавление)

### Этапы работы над проектом

1) Импортирование неодходимых библиотек.
2) Подгрузка данных и обработка данных (удаление пропусков, преобазование признаков).
3) Построение логистической регрессии на всех числовых признаках.
4) Отбор столюцов с помощью рекурсивного исключения признаков (RFE) и обучение модели на них.
5) Отбор столбцов с помощью выбора k-лучших переменных (SelectKBest) и обучеие модели на них.
6) Сравнение моделей на основании полученных метрик и выбор оптимальной.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Оглавление)

### Структура проекта

[data](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/data) - папка с исходными табличными данными

[HW-4.ipynb](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/HW-4.ipynb) - jupyter-ноутбук, с кодом проекта

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Оглавление)

### Результат

Было построено 3 варианта модели логистической регрессии и выбрана оптимальная.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Оглавление)

### Выводы

В процессе выполнения кейса первоначальные данные были:

* Загружены и подготовлены;
* Были отобраны признаки с помощью RFE и SelectKBest;
* Было построено несколько моделей машинного обучения;

Предпочтение было отдано модели для всех числовых признаков, так как она более детализирована, но по показателям качества различия незначительны с моделью на отобранных SelectKBest 3-х признаках. 

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-4/README.md#Оглавление)
