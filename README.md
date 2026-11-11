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
```Python
# Register No: 26016105
# Developed By: Yuvethika V
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat, 1)
print(f"{ans:.2f}")

Program to find 2-norm of a matrix.

Developed by: Yuvethika.V
RegisterNumber: 26016105
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Type your code here
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print(f"{ans:.2f}")

# Infinity Norm of a Matrix

#Developed by: Yuvethika V
#Register No: 26016105

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print(f"{ans:.2f}")

##Output:

### 1-Norm of a Matrix

<img width="908" height="525" alt="image" src="https://github.com/user-attachments/assets/e8089e1c-a63a-41a0-b42d-f9290b1ddc86" />
<img width="627" height="211" alt="image" src="https://github.com/user-attachments/assets/d3fa2ef8-7a2d-4f81-bd73-9c19bf158e9d" />

### 2-Norm of a Matrix

<img width="877" height="682" alt="image" src="https://github.com/user-attachments/assets/b7b79967-fa76-4126-bce1-58e35275c84e" />
<img width="530" height="257" alt="image" src="https://github.com/user-attachments/assets/7dce37f0-586b-46e4-a25d-522235c0a1c4" />

### Infinity Norm of a Matrix

<img width="1017" height="477" alt="image" src="https://github.com/user-attachments/assets/55a23d78-1201-42da-9222-7d41c5ca894b" />
<img width="917" height="207" alt="image" src="https://github.com/user-attachments/assets/99a3fc36-a578-4a80-98c3-55954d503d5c" />

##Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
