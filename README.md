# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module using an alias np
### Step 2: 
Get the input usimg array function
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and vectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Vanitha S
#RegisterNumber: 21222210057
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)
```
## Output:
![Screenshot (102)](https://user-images.githubusercontent.com/119557985/230761790-c0ff91d6-57e7-4693-b99c-8fa0c708dd68.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
