## Оглавление

[1. Описание проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Описание-проекта)\
[2. Краткая информация о данных](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Краткая-информация-о-данных)\
[3. Этапы работы над проектом](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Этапы-работы-над-проектом)\
[4. Структура проекта](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Структура-проекта)\
[5. Результат](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Результат)\
[6. Выводы](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Выводы)

### Описание проекта

Необходимо реализовать классификацию спам-сообщений с использованием готовых функций.

В библиотеке sklearn есть несколько байесовских классификаторов:

*GaussianNB* — самый простой вариант, работает с непрерывными признаками;
*MultinomialNB*  — работает с категориальными признаками, текстами и несбалансированными выборками;
*ComplementNB* — улучшенная версия MultinomialNB, стабильно показывает более высокое качество в задачах классификации текстов;
*BernoulliNB* — версия для работы с бинарными признаками;
*CategoricalNB* — работает с категориальными признаками, предполагает кодировку данных через OrdinalEncoder.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Оглавление)

### Краткая информация о данных

Исходный датасет представляет собой csv файл весом 4 КБ. Количество строк - 3000, столбцов - 2. Тип данных int64 и object, в столбцах присутствуют пропуски.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Оглавление)

### Этапы работы над проектом

1) Импортирование неодходимых библиотек.
2) Подгрузка и подготовка данных.
3) Определение целевой переменной и предикторов.
4) Реализовать обучение модели наивного байесовского классификатора;
5) Оценить качество модели с помощью кривой ROC-AUC;
6) Оценить качество полученной модели с помощью метрики F1.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Оглавление)

### Структура проекта

[data](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/data) - папка с исходными табличными данными

[HW-9.ipynb](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/HW-9.ipynb) - jupyter-ноутбук, с кодом проекта

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Оглавление)

### Результат

Была обучена модель наивного байесовского классификатора и построена визуализация с помощью кривой ROC, также реализована функция поиска оптимального гиперпараметра для наивного байесовского классификатора.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Оглавление)

### Выводы

В процессе выполнения задачи:
- Данные были загружены, проанализированы и подготовлены к построению модели;
- Реализовано обучение модели наивного байесовского классификатора;
- Проведена оценка качества модели с помощью кривой ROC-AUC;
- Реализована функция поиска оптимального гиперпараметра для наивного байесовского классификатора.

Подобрано лучшее значение гиперпараметра a = 0.35 - даёт более высокий F1 на тестовой выборке, а значит улучшено качество модели.

:arrow_up:[к оглавлению](https://github.com/senami27/Skillfactory_DST/blob/master/SF_DST/Practice-9/README.md#Оглавление)
