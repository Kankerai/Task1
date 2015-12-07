# Task1
Task for multiple programming languages
This task is intended to help to learn some basics of matrix manipulations. This is not a typical math task, but some practical issue from game developing field. Initially it was suggested to define this task with help of C++. However it's interesting to know is it possible to resolve it with some other language. Feel free to add files with decisions for this task in any language you know. In case if you have found file in language you know feel free to refactor it. Finally it would be interesting to see which way is more elegant.


THE TASK:

Two dimensional matrix is given. Any matrix element is an integer between 0 and 5. All decisions of this matrix should be found. As a decision should be considered an array of neighbour matrix elements with the total sum of 10. Neighbours can be in row as well as in a column, but not in diagonal. Any matrix element can be the first element of an array and can be used only once.
Among all decisions you should choose the most valued. The value of decision should be find with help of following formula:
firs element x 1000 + second element x 100 + third element x 10 + fourth element


EXAMPLE:
    _             _
   |  0 1 2 3 4 5  |
   |  1 2 3 4 5 0  |
   |_ 2 3 4 5 1 5 _|


[1234] - value is 1234
[4321] - value is 4321
