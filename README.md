# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the inbuilt in function for calculation.
### Step 2:
Prepare the lists from each equation and assign in np.array.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the module
## Program:
```
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues,eigenvectors=np.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:
![Screenshot 2024-11-10 220733](https://github.com/user-attachments/assets/83ea7a01-3e85-423c-a8ab-68c257032b65)
![Screenshot 2024-11-10 220757](https://github.com/user-attachments/assets/aec5b3c3-cb5a-43c0-9080-888ce1441188)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
