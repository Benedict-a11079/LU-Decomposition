# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
![lu decomposition]()
[[ 1.          0.          0.        ]
 [ 0.625       1.          0.        ]
 [ 0.5        -0.10810811  1.        ]]
[[ 8.         9.         1.       ]
 [ 0.        -4.625      7.375    ]
 [ 0.         0.         7.2972973]]

 [ 0.875  1.125 -0.125]


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

