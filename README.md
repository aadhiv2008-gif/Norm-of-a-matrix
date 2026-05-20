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
# Register No: 212225040002
# Developed By: Aadhithya V
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Aadhithya V 
RegisterNumber: 212225040002
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Aadhithya V 
RegisterNumber: 212225040002
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1213" height="671" alt="Screenshot 2026-05-20 105531" src="https://github.com/user-attachments/assets/e1d3981a-35df-4cb3-b79f-114a8a200f89" />
<img width="1226" height="346" alt="Screenshot 2026-05-20 105549" src="https://github.com/user-attachments/assets/720212ea-397a-49dd-9468-eccadf9b2537" />


### 2-Norm of a Matrix
<img width="1220" height="737" alt="Screenshot 2026-05-20 105605" src="https://github.com/user-attachments/assets/103a90a2-f205-4b5d-b167-7b608cea49db" />
<img width="1223" height="365" alt="Screenshot 2026-05-20 105620" src="https://github.com/user-attachments/assets/4d1c1730-b54e-406c-9185-ab19f5614c84" />

### Infinity Norm of a Matrix
<img width="1221" height="624" alt="Screenshot 2026-05-20 105631" src="https://github.com/user-attachments/assets/6dda706f-0367-4e58-a2f3-c654815843ec" />
<img width="1221" height="334" alt="Screenshot 2026-05-20 105646" src="https://github.com/user-attachments/assets/373a695c-3822-4ab4-a6cf-0a7e7fa93b9e" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
