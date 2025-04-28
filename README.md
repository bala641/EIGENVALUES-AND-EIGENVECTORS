# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy library.
### Step 2: Create the matrix a.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors nicely.

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: BALA B 
#RegisterNumber:212224100005
~~~python
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
~~~
## Output:
![image](https://github.com/user-attachments/assets/76ceae9e-0596-4fe6-8624-989c70bfc3cd)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
