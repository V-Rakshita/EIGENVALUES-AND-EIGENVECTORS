# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
import numpy as np
a = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(a)  #returns two values
print("Eigen values are {} and Eigen Vectors are {}".format(values, vectors))
```

## Output:
![EIGEN VALUES AND EIGEN VECTORS](https://github.com/user-attachments/assets/61b5d764-a67a-438d-8fdf-d0a81c2a0318)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
