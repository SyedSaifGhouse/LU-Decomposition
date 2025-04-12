# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Initialize L and U matrices
2. For each row ,eliminate variables below the pivot
3. Update L and U matrices
4. Return L and U

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SYED SAIF SYED GHOUSE
RegisterNumber: 212224230286'''
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SYED SAIF SYED GHOUSE
RegisterNumber: 212224230286'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv= lu_factor(A)
X= lu_solve((lu,piv),b)
print(X)
```

## Output:
1.
![Screenshot 2025-04-12 075642](https://github.com/user-attachments/assets/3c0eef56-92d6-4546-b1fe-7c0c21504bee)
.
![Screenshot 2025-04-12 075704](https://github.com/user-attachments/assets/a026cbad-db47-4194-8ac3-12eddb90eba0)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

