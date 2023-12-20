# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the lists from each linear equation and assign in np.array().
### Step 3: 
using the np.linalg.matrix_rank(),we can find the solution.
### Step 4: 
End the program
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: VINNUSH KUMAR L S
#RegisterNumber:23012349
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
#eig()fun return two values(value,vector)
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/vinnush147/EIGENVALUES-AND-EIGENVECTORS/assets/147139234/5274ab66-25b0-42db-9b24-062e2b02a167)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
