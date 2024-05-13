# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 
3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
# 1-Norm of a Matrix
```
#Developed:Navinkumar v
#Register no:212223230141

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
#Developed by:Navinkumar v
#RegisterNumber:212223230141

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 3-Infinity Norm of a Matrix
```
#Developed:Navinkumar v
#Register no:212223230141

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/navinofficial/Norm-of-a-matrix/assets/151710204/1272159a-c979-4157-a084-0ad9ee043243)
### 2-Norm of a Matrix
![image](https://github.com/navinofficial/Norm-of-a-matrix/assets/151710204/28cc16b9-a018-4fea-b3ac-5270f47ec4f8)
### Infinity Norm of a Matrix
![image](https://github.com/navinofficial/Norm-of-a-matrix/assets/151710204/377abbde-d59f-4c6b-b3d4-98a104409ae7)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
