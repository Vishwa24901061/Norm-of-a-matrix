# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### program-1

1. Get the input matrix using np.array()   

2. Find the 1-norm of the matrix using np.linalg.norm()

3. Print the norm of the matrix in two decimal places.
### program-2

1.Get the input matrix using np.array()

2.Find the 2-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.
### program-3

1.Get the input matrix using np.array()

2.Find the infinity-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212224110062
# Developed By: VISHWA V
# 1-Norm of a Matrix

'''
#Program to find infinity-norm of a matrix.
#Developed by: VISHWA V
#RegisterNumber: 212224110062
'''
import numpy as np
matrix=eval(input())
matrix = np.array(matrix)
norm = np.linalg.norm(matrix, ord=1)
print(f"{norm:.2f}")
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: VISHWA V
RegisterNumber: 212224110062
'''
import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,2)
L2_Norm_of_matrix=f"{ans:.2f}"
print(L2_Norm_of_matrix)
```

# Infinity Norm of a Matrix
```
'''
Program to find the Infinity of a matrix and display the result in two decimal places.
Developed by: VISHWA V
RegisterNumber: 212224110062
'''
import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
Norm_of_matrix=f"{ans:.2f}"
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2025-05-11 203604.png>)

### 2-Norm of a Matrix
![alt text](<Screenshot 2025-05-11 203614.png>)

### Infinity Norm of a Matrix
![alt text](<Screenshot 2025-05-11 203623.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
