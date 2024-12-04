# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X

## Program:
(i) To find the L and U matrix
```
*/
Program to find the L and U matrix.
Developed by: Tharshini
RegisterNumber: 24900038
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Tharshini
RegisterNumber: 24900038
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
*/
```

## Output:
![lu decomposition]()![Screenshot 2024-11-30 233405](https://github.com/user-attachments/assets/c789e251-f346-4e64-bb32-0affc7b642eb)
![Screenshot 2024-12-04 231008](https://github.com/user-attachments/assets/01190ea2-14a4-4f88-8187-db276f15f9d1)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

