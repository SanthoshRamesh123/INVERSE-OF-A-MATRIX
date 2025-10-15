# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Input Matrix A (square matrix). 
### Step 2: Check: Compute the determinant of A.f it is zero, print that the matrix is non-invertible and stop.
### Step 3:  Compute: If the determinant is non-zero, use np.linalg.inv(A) to compute the inverse.
### Step 4: Output: Print the inverse matrix.

## Program:
~~~python
#Program to find the inverse of a matrix.
#Developed by: SANTHOSH R
#RegisterNumber: 212224230249

import numpy as np
A = [[1,0,3],[-1,2,-2],[2,3,-1]]
inv = np.linalg.inv(A)
print(inv)
~~~
## Output:
<img width="1289" height="841" alt="Screenshot 2025-10-15 183843" src="https://github.com/user-attachments/assets/40604225-de5f-4a5a-b821-36ba221087dd" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

