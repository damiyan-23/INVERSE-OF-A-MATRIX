# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

### Step 2: 

import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])

### Step 3: 

r=np.linalg.inv(A)

### Step 4: 

print(r)

## Program:
<img width="1262" height="707" alt="image" src="https://github.com/user-attachments/assets/87558cf3-3cc0-43db-bc08-0e0d9c88c9e4" />

## Output:
<img width="1252" height="225" alt="image" src="https://github.com/user-attachments/assets/fe9af81d-bb80-4a22-809b-1730dd406bb4" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

