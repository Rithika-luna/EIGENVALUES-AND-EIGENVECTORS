# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.
### Step 2: 
Import the NumPy library using import numpy as np.

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Use the np.linalg.eig() function to calculate the eigenvalues and eigenvectors of the given matrix. It returns two results: the first represents eigenvalues and the second represents eigenvectors.
### Step 5: 
Display the given matrix, eigenvalues and eigenvectors using the print() statement.
### Step 6:
Stop the program.
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:

<img width="1467" height="798" alt="image" src="https://github.com/user-attachments/assets/9bdb87c1-7e57-4ee6-b39b-80b0139ae2f3" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
