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
```
# Register No:212223230133
# Developed By: NARASIMHAN S 
# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.array(mat)
norm= np.linalg.norm(ans,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.array(mat)
norm= np.linalg.norm(ans,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.array(mat)
norm= np.linalg.norm(ans,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-16 131702](https://github.com/Narasimhan05/Norm-of-a-matrix/assets/132819871/3e02e893-cb96-4cd8-b341-aa2092496814)

### 2-Norm of a Matrix

![Screenshot 2024-05-16 131717](https://github.com/Narasimhan05/Norm-of-a-matrix/assets/132819871/f9a741ae-a3ec-4cfb-973a-4546148b604c)

### Infinity Norm of a Matrix

![Screenshot 2024-05-16 131728](https://github.com/Narasimhan05/Norm-of-a-matrix/assets/132819871/ee6fbbb5-a0f2-4738-9b06-607a59548dc5)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
