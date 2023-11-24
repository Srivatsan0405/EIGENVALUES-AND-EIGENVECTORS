# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SRIVATSAN V
#RegisterNumber:23000970
import numpy as np
a=[-2,2,-3],[2,1,-6],[-1,-2,0]
val,vect=np.linalg.eig(a)
print("Eigen values are",val,"and Eigen Vectors are",vect)
```

## Output:
![Screenshot 2023-11-24 114137](https://github.com/Srivatsan0405/EIGENVALUES-AND-EIGENVECTORS/assets/139841630/707d4341-564c-43c5-ab97-49392301c2fa)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
