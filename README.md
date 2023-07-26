# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module and scipy.linalg module to use the built-in functions for calculation.
2.Prepare the lists from each linear equations and assign in np.array().
3.Perform scipy.linalg.lu to find the pivot table, lower triangle and upper triangle matrix.
4.End the Program. 

## Program:
(i) To find the L and U matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Daksha Subbaian
RegisterNumber: 23003584
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Daksha Subbaian
RegisterNumber: 23003584
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![output](/output05\)1..png)
![output](/output05\)2..png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

