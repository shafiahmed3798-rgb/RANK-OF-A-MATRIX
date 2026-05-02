# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library.
### Step 2: Define the given matrix
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix.
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(a)
print(rank)
#Program to find the rank of a matrix.
#Developed by: SHAFI AHMED M S
#RegisterNumber:212225240143
```
## Output:

<img width="1264" height="292" alt="image" src="https://github.com/user-attachments/assets/0ea6b6a2-a26b-49af-9acf-df27d90fe553" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

