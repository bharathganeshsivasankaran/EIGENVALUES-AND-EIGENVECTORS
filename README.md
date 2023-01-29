# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import  numpy library as np.
### Step 2: create a matrix using array() function.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Get the output and out the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: BHARATHGANESH.S
#RegisterNumber:22001588
```
```
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
val,vec=np.linalg.eig(a)
print('''Eigen values are {} and Eigen Vectors are {} '''.format(val,vec))
```

## Output:
![OUTPUT 4](https://user-images.githubusercontent.com/119478098/215315554-f49dbdb6-58c2-4281-86f1-5538be80ad1a.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
