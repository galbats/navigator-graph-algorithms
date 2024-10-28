# SimpleNavigator

## Описание 

В проекте представлен консольный интерфейс, в котором реализовано несколько основных алгоритмов на графах. Он покрывает следующий функционал:

1. Загрузка исходного графа из файла.
2. Обход графа в ширину с выводом результата обхода в консоль.
3. Обход графа в глубину с выводом результата обхода в консоль.
4. Поиск кратчайшего пути между произвольными двумя вершинами с выводом результата в консоль.
5. Поиск кратчайших путей между всеми парами вершин в графе с выводом результирующей матрицы в консоль.
6. Поиск минимального остовного дерева в графе с выводом результирующей матрицы смежности в консоль.
7. Решение задачи коммивояжера с выводом результирующего маршрута и его длины в консоль.

## Структура проекта

```
.
├── Makefile
├── data
│   ├── g1.txt
│   ├── g2.txt
│   ├── g3.txt
│   └── graph.txt
├── main.py
├── queue.py
├── requirements.txt
├── s21_graph.py
├── s21_graph_algorithms.py
├── stack.py
├── test.py
└── visual.py
```


## Запуск проекта

Установите необходимые зависимости в виртуальном окружении:

```
pip install -r requirements.txt
```

Выполните команду:

```
make
```

Чтобы запустить тесты, используйте команду:

```
make test
```

Тесты запускаются с помощью unittest, а также генерируется отчет о покрытии кода.

Для визуализации графов можно использовать следующую команду:

```
python visual.py
```