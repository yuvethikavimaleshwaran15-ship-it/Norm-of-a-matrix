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
# Register No : 26016105
# Developed By: Yuvethika V
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat, 1)
print(f"{ans:.2f}")

# 2-Norm of a Matrix

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

```
## Output:
### 1-Norm of a Matrix
<br><img width="908" height="525" alt="Screenshot 2026-11-11 113622" src="https://github.com/user-attachments/assets/db675c22-edb2-4c95-9ca7-7cdd4f18998e" />

<br><img width="627" height="211" alt="Screenshot 2026-11-11 113642" src="https://github.com/user-attachments/assets/f386d022-a459-4265-8efc-e3d7f2f554ff" />

<br>

### 2-Norm of a Matrix
<br><img width="877" height="682" alt="Screenshot 2026-11-11 113528" src="https://github.com/user-attachments/assets/32e32664-d77e-4b3d-8b76-f887d89af20e" />

<br><img width="530" height="257" alt="Screenshot 2026-11-11 113544" src="https://github.com/user-attachments/assets/8f006746-2603-4e11-b037-9189398903f1" />

<br>

### Infinity Norm of a Matrix
<br><img width="1017" height="477" alt="Screenshot 2026-11-11 113421" src="https://github.com/user-attachments/assets/86c570ae-dad9-4add-a6f3-a6789dc77c73" />

<br><img width="917" height="207" alt="Screenshot 2026-11-11 113454" src="https://github.com/user-attachments/assets/b05a2cef-e8dd-4a7b-a332-423706163d14" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
