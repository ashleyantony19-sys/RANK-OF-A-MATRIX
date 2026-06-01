# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation 
### Step 2:  Prepare the lists from each linear equations and assign in np.array()  
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: ASHLEY ANTONY
#RegisterNumber: 212225220013
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
MatrixA=np.array([[5,-3,10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(MatrixA)
print(rank)
```
## Output:


<img width="574" height="213" alt="WhatsApp Image 2026-06-01 at 9 33 43 AM" src="https://github.com/user-attachments/assets/63eb42d7-7633-4034-ad80-f9e7201d97b1" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

