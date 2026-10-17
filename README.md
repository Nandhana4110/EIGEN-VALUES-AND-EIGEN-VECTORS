# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the given matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
## Output:
<img width="1335" height="857" alt="image" src="https://github.com/user-attachments/assets/e1c02fb6-58df-4060-b3c4-44ca2f3042cc" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
