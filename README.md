# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the required NumPy library.

Step 2: Define the given matrix using np.array().

Step 3: Using the np.linalg.matrix_rank(), find the rank of the given matrix.

Step 4: Display the rank of the matrix as the output.
## Program:
```
#Program to find the rank of a matrix.
#Developed by:DINESH S
#RegisterNumber:212224240038
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
C = np.linalg.matrix_rank(A)
print(C)
```
## Output:
<img width="1866" height="971" alt="image" src="https://github.com/user-attachments/assets/7460c132-330c-4d32-a92b-f860c0c4e3f3" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

