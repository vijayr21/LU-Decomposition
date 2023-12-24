# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step 1:
 In this step, you initialize the matrix A for which you want to perform LU decomposition.

## step 2:
Perform LU Decomposition

## step 3:
Display the Result

## step 4:
Understanding the Result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: VIJAY R
RegisterNumber: 23013759
'''
import numpy as np
from scipy.linalg import lu
a= np.array(eval(input()))
p,L,u= lu(a)
print(L)
print(u)
```

(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: VIJAY R
RegisterNumber: 23013759
'''
import numpy as np
from scipy.linalg import lu
a= np.array(eval(input()))
p,L,u=lu(a)
B=np.array([4,5,7])
X=np.linalg.solve(a,B.T)
print(X)
```


## Output:
1.![Screenshot 2023-12-24 201043](https://github.com/vijayr21/LU-Decomposition/assets/149347607/fbaf26f6-dc61-4d38-9c48-bba735f619fa)
2.![Screenshot 2023-12-24 201106](https://github.com/vijayr21/LU-Decomposition/assets/149347607/54541a9d-c0aa-45af-a5e1-22518e8219ea)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

