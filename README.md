# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import the numpy module to use the built in function for calculation
### Step 2: prepare the list from the given matrix and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="1310" height="896" alt="image" src="https://github.com/user-attachments/assets/e18a416f-b311-40e7-9888-06a55ce5aa6a" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

