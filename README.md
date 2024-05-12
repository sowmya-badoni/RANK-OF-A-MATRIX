# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 

Import the numpy module to use the built-in functions for calculation.

### Step 2: 

Prepare the lists from each equation and assign in np.array

### Step 3:

Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4: 

End the program
## Program:
#Program to find the rank of a matrix.

#Developed by: SOWMYA BADONI

#RegisterNumber:212223230211

import numpy as np

A= np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])

rank = np.linalg.matrix_rank(A)

print(rank)

## Output:
![Screenshot 2024-05-12 173451](https://github.com/sowmya-badoni/RANK-OF-A-MATRIX/assets/152136324/370a85c1-3f7d-442d-8e0b-b911f1e33f26)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

