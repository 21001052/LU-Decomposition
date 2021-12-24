# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. step 1:start
2. step 2:get an input from user
3. step 3: display the value
4.step 4:stop 

## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: thamaraiselvan v
RegisterNumber: 21001052
*/
```
~~~
import numpy as np
import scipy
from scipy.linalg import lu
A =eval(input())
P,L,U=lu(A)
print(L)
print(U)
~~~
~~~
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv= lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)
~~~

## Output:
![lu decomposition](/tham.png)
![lu decomposition](/tham2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

