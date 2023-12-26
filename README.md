# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.
### Step 2: 
Prepare the lists from the each inverse of a matrix and design in ip.array(). 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SURYAMALAR V
#RegisterNumber: 23013656
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![image](https://github.com/suryamalarv/EIGENVALUES-AND-EIGENVECTORS/assets/145742486/0df3b993-54a7-4f9d-85f5-e3d9138fe20d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
