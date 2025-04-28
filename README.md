# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start with a square matrix A (n × n matrix).
### Step 2: 
Set up the characteristic equation:
Solve for λ (eigenvalues) by solving:

det
(
𝐴
−
𝜆
𝐼
)
=


where:

det = determinant

I = identity matrix of the same size as A

λ = eigenvalue
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Find eigenvectors for each eigenvalue:

For each eigenvalue λ, solve the system:

(
𝐴
−
𝜆
𝐼
)
𝑋 = 0

where X is the eigenvector corresponding to λ.

This is typically a system of homogeneous linear equations.

Find the non-trivial (non-zero) solutions.

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
![image](https://github.com/user-attachments/assets/36cfb654-3474-4e18-98ab-6d1cbf3a0b46)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
