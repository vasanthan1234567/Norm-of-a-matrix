# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
i.One norm of the matrix

1. Get the input matrix using np.array()   
2. Find the 1-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in one decimal places.

ii.Two norm of the matrix

1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.

iii.Infinity norm of the matrix

1. Get the input matrix using np.array()   
2. Find the infinity-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in decimal places.

## Program:

```
Python
# Register No:24900250
# Developed By:vasanthan N

# 1-Norm of a Matrix

import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)


# 2-Norm of a Matrix

import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")


# Infinity Norm of a Matrix

import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)


```
## Output:
### 1-Norm of a Matrix
![output](<Screenshot 2025-01-05 175243.png>)

### 2-Norm of a Matrix
![output](<Screenshot 2025-01-05 175317.png>)

### Infinity Norm of a Matrix
![output](<Screenshot 2025-01-05 175330.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
