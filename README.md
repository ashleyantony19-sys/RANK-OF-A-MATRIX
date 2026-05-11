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
import numpy as np

A = np.array([[1, 2, 3],
              [4, 5, 6],
              [7, 8, 9]])

rank = np.linalg.matrix_rank(A)

print("The given matrix is:")
print(A)

print("Rank of the matrix is:", rank)
```
## Output:



<img width="1054" height="513" alt="Screenshot 2026-05-11 184236" src="https://github.com/user-attachments/assets/4159816c-76fa-4748-9249-ed28c444f611" />






<img width="995" height="450" alt="Screenshot 2026-05-11 184245" src="https://github.com/user-attachments/assets/7c435c10-225e-4f90-b65b-623eb28172cb" />





## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

