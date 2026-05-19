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

# 1-Norm of a Matrix
'''
Program to find 1-Norm of a matrix
Developed By: SAHANA S
Register Number: 212225230236
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SAHANA S
RegisterNumber: 212225230236
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
'''
Program to find infinity norm of a matrix.
Developed by: SAHANA S
RegisterNumber: 212225230236
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print("{:.2f}".format(norm))
```

## Output:
### 1-Norm of a Matrix
<img width="642" height="196" alt="image" src="https://github.com/user-attachments/assets/eb487437-98c1-47af-b6b0-65beeb958f2a" />


### 2-Norm of a Matrix
<img width="704" height="240" alt="image" src="https://github.com/user-attachments/assets/aa4a16ea-021c-4e56-80e0-bffd7673f481" />


### Infinity Norm of a Matrix
<img width="749" height="194" alt="image" src="https://github.com/user-attachments/assets/6a0f112d-368b-43bf-8f2b-f3d505f97312" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
