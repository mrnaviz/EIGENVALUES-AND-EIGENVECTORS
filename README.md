# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Importing numpy as np
### Step 2:
Assigning variable and storing the matrix values
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
ENd the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: NAVEEN KUMAR.B
#RegisterNumber:212222230091
import numpy as np
A=([[2,2],[1,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![image](https://user-images.githubusercontent.com/123350791/230767367-351871d7-6303-4e44-b0ef-32c9041f4461.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
