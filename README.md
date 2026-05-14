# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Start the program and import the NumPy library.
### Step 2: Input/Define the given matrix A=[[4,2],[2,4]].
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and associated eigenvectors, then Stop the program. 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Cassandra Suzanne F
#RegisterNumber: 212225240027
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np


A = np.array([[4, 2],
              [2, 4]])


eigenvalues, eigenvectors = np.linalg.eig(A)


print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)

## Output:<img width="1292" height="256" alt="image" src="https://github.com/user-attachments/assets/38a766d0-a6d1-4173-bcc7-4e34e4d2de07" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
