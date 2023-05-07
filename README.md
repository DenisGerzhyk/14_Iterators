# 14_Iterators

1).
This program defines a Rectangle class that can be used to calculate the area of rectangles, compare their areas and perform arithmetic operations on their areas.

The __init__() method initializes the width and height attributes of the rectangle object.
The get_square() method calculates the area of the rectangle.
The __eq__() method compares the areas of two rectangle objects.
The __add__() method adds the areas of two rectangle objects.
The __mul__() method multiplies the area of a rectangle object by a scalar value.
The __str__() method returns a string representation of a rectangle object.
Several rectangle objects are created and their areas are calculated and compared using the above methods.

2).
This program defines a Fraction class that can be used to perform arithmetic operations on fractions.

The __init__() method initializes the numerator and denominator attributes of the fraction object.
The get_fraction() method returns a tuple of the numerator and denominator of the fraction object.
The __mul__() method multiplies a fraction object by a scalar value.
The __add__() method adds a scalar value to a fraction object.
The __sub__() method subtracts a scalar value from a fraction object.
The __eq__() method compares two fraction objects.
The __gt__() method compares two fraction objects and returns True if the first fraction is greater than the second.
The __lt__() method compares two fraction objects and returns True if the first fraction is less than the second.
Several fraction objects are created and arithmetic operations are performed on them using the above methods.

3).
This program defines a Fibonacci class that can be used to generate a list of Fibonacci numbers up to a given limit.

The __init__() method initializes the limit attribute of the Fibonacci object.
The add() method generates a list of Fibonacci numbers up to the limit attribute of the Fibonacci object.
A Fibonacci object is created and the add() method is called to generate a list of Fibonacci numbers up to the limit.

4).
This program defines a Matrix class that can be used to iterate over the elements of a matrix.

The __init__() method initializes the matrix attribute of the Matrix object.
The __iter__() method iterates over the elements of the matrix and yields each element one at a time.
A matrix object is created and the elements of the matrix are iterated over using a for loop and the Matrix object.

5).
This program defines a Pairs class that can be used to generate pairs of elements from two lists.

The __init__() method initializes the list1 and list2 attributes of the Pairs object.
The generate() method generates pairs of elements from list1 and list2 using the zip() function.
A Pairs object is created and the generate() method is called to generate pairs of elements from list1 and list2.

6).
This program defines a Files class that can be used to read the contents of multiple files.

In the first implementation of the Files class:
The __init__() method initializes the file1, file2, and file3 attributes of the Files object.
The open_read() method opens each file in read mode and yields the contents of each file one at a time.
A Files object is created and the open_read() method is called to read the contents of each file.
In the second implementation of the Files class:
The __init__() method initializes a files attribute of the Files object that
