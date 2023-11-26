# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
start the program
### Step 2: 
Assign np.array() in eigen values and eigen vectors.


### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print both the values and vectors,then end the program.



## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MOULIDHAR.G
#RegisterNumber:23009285
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))


```

## Output:
![image](https://github.com/moulidharyadav/EIGENVALUES-AND-EIGENVECTORS/assets/147078316/604c8dfc-ec49-4c84-8572-0b164c245235)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
