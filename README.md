# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module as np.
### Step 2: Store the given matrix in array using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the calculated eigenvalue and eigenvector.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Shreeshanth R
#RegisterNumber: 212225040411

import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="1337" height="177" alt="image" src="https://github.com/user-attachments/assets/a1de24a7-5db4-4c55-bc7c-4afdcff22d3a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
