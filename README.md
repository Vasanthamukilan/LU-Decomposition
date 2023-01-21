# LU Decomposition 
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step1:
Import the numpy module to use the built-in functions for calculation
## Step2:
Prepare the list for a matrix and assign in np.array()
## Step3:
Using the scipy.linalg, we can find the L and U matrix and LU decomposition of a matrix
## Step4:
End the program
## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by:Vasanthamukilan.M
RegisterNumber:22001986
'''
import numpy as np   #from numpy import array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by:Vasanthamukilan.M 
RegisterNumber:22001986
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```
## Output:
(i)
!['output'](/Screenshot_20230121_105603.png)
(ii)
!['output'](/Screenshot_20230121_105748.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

