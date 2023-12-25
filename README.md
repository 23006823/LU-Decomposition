# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.STEP:
Import numpy module to use the bulit-in functions for calcukation
2. STEP:
From scipy.linalg module import lu to find the L and U matrix
3.STEP:
Get a input from the user and apply lu function.
4.STEP:
Print L for L matrix and print U for U matrix
5.STEP:
End of program.
## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
import numpy as np
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu=lu_factor(A)
x=lu_solve(lu,B)
print(x)
```

## Output:
![image](https://github.com/23006823/LU-Decomposition/assets/138971409/0082eb25-16b0-4db8-933f-347de1dfd5ab)
![image](https://github.com/23006823/LU-Decomposition/assets/138971409/6bc2d42e-411b-49c9-82bf-3afd5f5d4bcc)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

