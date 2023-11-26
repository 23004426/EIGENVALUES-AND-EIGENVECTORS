# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library in your Python script.
### Step 2: Define your matrix for which you want to find the eigenvalues and eigenvectors.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the results

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Tirupathi Jayadeep
#RegisterNumber:23004426
import numpy as np
a=[[2,2],[1,3]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:

![Screenshot 2023-11-26 061242](https://github.com/23004426/EIGENVALUES-AND-EIGENVECTORS/assets/144979327/1e5b0eb5-2df8-4def-96ab-facac7d19af1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
