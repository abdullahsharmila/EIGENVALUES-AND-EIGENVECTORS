# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the required libraries
### Step 2: 
Define a matrix A
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Display the calculates eigen values and eigen vectors 

## Program:
``````
#Program to find the eigen values and eigen vectors.
#Developed by:abdullah.R 
#RegisterNumber:23013613
import numpy as np
matrix=np.array([[4,2],
                [2,4]])
values,vectors=np.linalg.eig(matrix)
print("Eigen values are" ,values ,"and Eigen Vectors are",vectors)
``````

## Output:
![Alt text](<Screenshot 2023-11-24 233350.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
