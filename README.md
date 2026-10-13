# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm: Inverse of the matrix
### Step1 : Read the input of the matrix  
### Step 2: Calculate the determinant of the matrix
### Step 3: Find the adjoint of the matrix
### Step 4: Divide the adjoint of the matrix by its determinant to obtain the inverse matrix

## Program:
###
Program to find the inverse of a matrix.
###
Developed by:hema.M
###
RegisterNumber:26018380
###
import os
###
os.environ["OPENBLAS_NUM_THREADS"]="1"
###
import numpy as np
###
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
###
b=np.linalg.inv(a)
###
print(b)
## Output:<img width="1263" height="842" alt="image" src="https://github.com/user-attachments/assets/2351b142-3e7d-4195-abaa-6cad2015315f" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

