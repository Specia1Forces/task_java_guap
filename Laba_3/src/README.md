# Задание 3. Наследование.

Напишите класс Matrix, реализующий матрицы и расширяющий его класс SquareMatrix, реализующий квадратные матрицы. В классах должны быть определены:

* конструктор с целочисленным параметром --- размером матрицы, создающий единичную матрицу;
* методы Matrix sum(Matrix) и Matrix product(Matrix), вычисляющие сумму и произведение матриц
* матрицы setElement(int row, int column, int value) и getElement(int row, int column), для 	обращения к 	элементам матрицы;
* метод 	toString() (Примечание: необходимо использовать StringArray или StringBuilder).

Напишите собственный класс исключения, расширяющий (наследующий) класс RuntimeException. Во всех конструкторах и методах должны бросаться исключения в тех случаях, когда соответствующая операция невозможна (например, при сложении матриц разных размеров). Исключения должны содержать информацию о том, какая именно проблема возникла. Достаточно хранить эту информацию в виде строки, возвращаемой методом getMessage().

Примените к написанной программе:
1. Разложите классы по пакетам.
2. Напишите слово final в тех случаях, где оно разумно.
3. Реализуйте для матриц метод equals().



