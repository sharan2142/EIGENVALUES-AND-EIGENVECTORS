# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy library
### Step 2: create a matrix using numpy
### Step 3: calc the result using np.linalg.inv
### Step 4: End the Program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: M Sharan Kumar
#RegisterNumber: 212225040403

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cf81a47f-96bb-426a-a661-4c436f193093" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
