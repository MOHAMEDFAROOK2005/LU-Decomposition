# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy
2.from scipy.linlag import lu,lu_factor,lu,solve.
3. solve using scipy.linlag(variable)
4. Print the output

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: MOHAMED FAROOK S
RegisterNumber: 23014058
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U =lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: MOHAMED FAROOK S
RegisterNumber: 23014058
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
A=np.array(a)
B=np.array(b)
result=lu_factor(A)
sol = lu_solve(result,B)
print(sol)
*/
```

## Output:
![image](https://github.com/MOHAMEDFAROOK2005/LU-Decomposition/assets/150319482/59dfb813-eccf-4a79-8af0-b4e0a3fa0203)
![image](https://github.com/MOHAMEDFAROOK2005/LU-Decomposition/assets/150319482/52ca035e-7920-4706-b274-ce9cebbf0281)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

