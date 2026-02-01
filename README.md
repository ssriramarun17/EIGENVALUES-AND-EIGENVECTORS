# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program 
### Step 2: Import the required library numpy
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the required eigen values

## Program:
```
import numpy as np

A = np.array([[2, 2],
              [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:
<img width="1261" height="836" alt="Screenshot 2026-02-01 153136" src="https://github.com/user-attachments/assets/ba6ada92-eaaf-4f3b-b593-0947dbdffd06" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
