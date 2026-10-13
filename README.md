# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : impot numpy and os module
### Step 2: get input
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the result

## Program:
### #Program to find the eigen values and eigen vectors.
### #Developed by: M.K. Jeevith
### #RegisterNumber:26018300
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as n
### a=n.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
### eigval,eigvec=n.linalg.eig(a)
### print("Eigen values are {} and Eigen Vectors are {}".format(eigval,eigvec))

## Output:<img width="1496" height="875" alt="Screenshot 2026-10-13 160629" src="https://github.com/user-attachments/assets/f0b9b77a-83a2-45cd-bd31-b7a4266ec28b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
