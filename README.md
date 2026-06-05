# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy library, which contains built-in mathematical functions for handling multi-dimensional arrays and matrix operations.
### Step 2: Create the given matrix by initializing a 2D array or matrix structure using NumPy's np.array() function.
### Step 3: Use the linear algebra module from NumPy (np.linalg.inv()) to compute the inverse of the defined matrix.
### Step 4: Print the calculated inverse matrix to the console to view the final output.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Adam N 
#RegisterNumber:212225230005
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(matrix)
print(inverse)
```
## Output:
<img width="1290" height="892" alt="image" src="https://github.com/user-attachments/assets/89075f0f-50c0-4540-ab09-b940459f9341" />
<img width="1417" height="825" alt="image" src="https://github.com/user-attachments/assets/7b9e6004-de2b-441f-97d6-a26028f86792" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

