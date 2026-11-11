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

# Output :
### 1-Norm of a Matrix
<img width="908" height="525" alt="Screenshot 2026-11-11 113622" src="https://github.com/user-attachments/assets/317ffaa2-d277-40dd-9fe2-71833cc0d93e" />
<img width="627" height="211" alt="Screenshot 2026-11-11 113642" src="https://github.com/user-attachments/assets/6210a864-5b80-4f09-af78-d0474628bde7" />

### 2-Norm of a Matrix
<img width="877" height="682" alt="Screenshot 2026-11-11 113528" src="https://github.com/user-attachments/assets/72d61a0a-5426-45d4-a2ec-76c0ce3d3fdf" />
<img width="530" height="257" alt="Screenshot 2026-11-11 113544" src="https://github.com/user-attachments/assets/08dc3f0e-5fed-424f-917f-27bf685b96e1" />

### Infinity Norm of a Matrix
<img width="1017" height="477" alt="Screenshot 2026-11-11 113421" src="https://github.com/user-attachments/assets/6b3fe5b0-9703-420f-a094-87e4f9811c86" />
<img width="917" height="207" alt="Screenshot 2026-11-11 113454" src="https://github.com/user-attachments/assets/99c0ff6a-2121-47b1-b732-ac533b14795d" />

# Result :
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
