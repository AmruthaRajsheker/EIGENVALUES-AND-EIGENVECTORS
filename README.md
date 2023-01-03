# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy
### Step 2: 
Initialize the values of matrix
### Step 3: 
Using the numpy.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Amrutha Rajsheker
#RegisterNumber: 22004501
import numpy 
a = numpy.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = numpy.linalg.eig(a)
print ("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![EVEV](https://user-images.githubusercontent.com/119475943/210364109-bc342ae7-2a59-48d8-8528-e07c5c0b69b5.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
