Day11
---
1.  Добавить в класс с методом трансформером массива вещественных чисел [перегруженную версию, принимающую делегат](https://github.com/RomanGutovec/NET1.A.2018.Gutovec.4/blob/master/Algorithms/TransformerToWords.cs). 
Проверить работу метода на [модульных тестах](https://github.com/RomanGutovec/NET1.A.2018.Gutovec.4/blob/master/Algorithms.Tests/TransformerToWordsTest.cs).
2.  Выполнить рефакторинг класса (с целью сокращения повторного кода) в [алгоритмах Евклида](https://github.com/RomanGutovec/NET1.A.2018.Gutovec.4/blob/master/Algorithms/EuclideanAlgorithm.cs) 
(рефакторинг возможен только в случае, когда все метод находятся в одном классе!). Интерфейс класса измениться не должен. 
Проверить работу существующих [модульных тестов](https://github.com/RomanGutovec/NET1.A.2018.Gutovec.4/blob/master/Algorithms.Tests/EuclideanAlgorithmTests.cs).
3.  В класс с алгоритмом сортировки не прямоугольной матрицы, принимающий как компаратор интерфейс, добавить [перегруженный метод](https://github.com/RomanGutovec/NET1.A.2018.Gutovec.7/blob/master/AlgorithmSort/BubbleSort.cs), 
принимающий как параметр делегат-компаратор, инкапсулирующий логику сравнения строк матрицы. 
Протестировать работу разработанного метода на примере сортировки матрицы, используя прежние критерии сравнения. 
Класс реализовать двумя способами (два отдельных класса), «замкнув» [в первом варианте](https://github.com/RomanGutovec/NET1.A.2018.Gutovec.7/blob/master/AlgorithmSort/BubbleSortDelegateOnInterface.cs) реализацию метода сортировки с делегатом на 
метод с интерфейсом (работу выполняет метод с параметром-интерфейсом, метод с делегатом его вызывает), 
[во втором](https://github.com/RomanGutovec/NET1.A.2018.Gutovec.7/blob/master/AlgorithmSort/BubbleSortInterfaceonDelegate.cs) – наоборот (работу выполняет метод с параметром-делегатом, метод с интерфейсом его вызывает).
