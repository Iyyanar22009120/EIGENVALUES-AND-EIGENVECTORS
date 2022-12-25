# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as convienience variable
### Step 2: 
Let assume  any variable
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the eigen values and eigen vectorss

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: IYYANAR S
#RegisterNumber:22009120

import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vectors))
```

## Output:
![OUTPUT](./Eigen%20values%20and%20Eigen%20vectors.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
