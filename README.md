# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
to find the rank of  matrix
### Step 2: 
we will transform the matrix into its echelon form
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
determine the rank of matrix by the number non-zero rows
## Program:
```
#Program to find the rank of a matrix.
#Developed by:YENUGANTI PRATHYUSHA 
#RegisterNumber:23009045
import numpy as np
a=np.array([[3,4,5],[1,1,2],[3,3,6]])
sol=np.linalg.matrix_rank(a)
print(sol)
```
## Output:
![image](https://github.com/prathyusharavi/RANK-OF-A-MATRIX/assets/147474424/eb411ec4-b081-47d6-aed8-791531903b3c)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

