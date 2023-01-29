# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
    Import the numpy module to use built-in function for calculations
### Step 2: 
    Prepare the list from matrix's each row and assign in np.array()
### Step 3:
    Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
    End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: JAYAKRISHNAN L B L
#RegisterNumber: 22003251
import numpy as np
A = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![image (25)](https://user-images.githubusercontent.com/120232371/215279864-827e4b8a-09fa-4755-bb54-742430024d59.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
