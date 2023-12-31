# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    	2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:

## 1-Norm of a Matrix:
```
Program to find 1-norm of a matrix.
Developed by: VENKATANATHAN P R
Register Number: 23000285

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## 2-Norm of a Matrix:
```
Program to find 2-norm of a matrix.
Developed by: VENKATANATHAN P R
RegisterNumber: 23000285

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Infinity Norm of a Matrix:
```
Program to find Infinity norm of a matrix.
Developed by: VENKATANATHAN P R
Register Number: 23000285

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
![image](https://github.com/23000285/Norm-of-a-matrix/assets/138970859/68c5f020-3b35-4744-bc62-b9a64ed44c84)

### 2-Norm of a Matrix
![image](https://github.com/23000285/Norm-of-a-matrix/assets/138970859/4977e80c-1124-4ade-bf7f-e6a626b7fdb4)

### Infinity Norm of a Matrix
![image](https://github.com/23000285/Norm-of-a-matrix/assets/138970859/fd485e00-f0e9-46d9-9eae-be2f07405338)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
