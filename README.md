# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculations
### Step 2: Prepare the lists from each linear equations ans assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: Swetha K

#RegisterNumber:212224230284
```
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```

## Output:

![Screenshot 2025-04-16 091341](https://github.com/user-attachments/assets/259e7cfd-8c4d-4c8a-9ba2-3a9beb9dbd0c)
![Screenshot 2025-04-16 091436](https://github.com/user-attachments/assets/2bae0909-45c6-480c-a131-dab1da4707b3)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
