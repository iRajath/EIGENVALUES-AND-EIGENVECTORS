# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module.
### Step 2: Assign the given matrix to a variable using `np.array()`.
### Step 3: Using the `np.linalg.eig()`,  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result.
### Step 5: End the Program.

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: S Rajath
#RegisterNumber: 24900186

import numpy as np

a = np.array([[2, -3, 0], [2, -5, 0], [0, 0, 3]])
values, vectors = np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:

![Screenshot 2024-12-04 143616](https://github.com/user-attachments/assets/0b31933c-49c2-487b-abb4-b7affc627fe6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
