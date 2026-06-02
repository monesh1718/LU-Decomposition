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
/*
Program to find the L and U matrix.
Developed by: monesh s
RegisterNumber: 212225040256

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
from scipy.linalg import lu

A = np.array(eval(input()), dtype=float)

P, L, U = lu(A)

print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: monesh s 
RegisterNumber: 212225040256
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"


import numpy as np
from scipy.linalg import lu_factor, lu_solve

A = np.array(eval(input()), dtype=float)
B = np.array(eval(input()), dtype=float)

lu, piv = lu_factor(A)
X = lu_solve((lu, piv), B)

print(X)
*/
```

## Output:
<img width="1198" height="197" alt="Screenshot 2026-06-02 175908" src="https://github.com/user-attachments/assets/91f5ac1f-401c-48a2-b7a0-08029c2c389f" />
<img width="1244" height="492" alt="Screenshot 2026-06-02 175853" src="https://github.com/user-attachments/assets/66dd0fa9-d4af-46ef-a4e2-a6cedf726502" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

