# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists for given matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```py
#Program to find the eigen values and eigen vectors.
#Developed by: Srinivas J
#RegisterNumber:212225230276
import numpy as np
A = np.array([[4, 2],[2, 4]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:
![alt text](<Screenshot 2026-02-10 113117.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
