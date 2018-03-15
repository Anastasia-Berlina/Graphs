# Graphs

Построение графа дорог города Владивосток.
Для запуска проекта нужны библиотеки jdom (для работы с xml файлами) и opencsv(для работы с csv файлами).

В папке "result" находится файл graph.svg - визуализация полученного графа, файл vertices.csv - содержащий 
id вершины и её декартовы координаты и файд edges.csv - содержит пары вида (id1,id2), где id1 - id вершины 
из которой исходит ребро графа, id2 - id вершины, куда приходит это ребро.
