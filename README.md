# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# Step 1: 
Import the NumPy module to access linear algebra functions.
# Step 2: 
Accept matrix input from the user and convert it into a NumPy array using np.array(eval(input())).
# Step 3:
For 1-Norm: Use the function np.linalg.norm(matrix, 1) to calculate the column-wise maximum absolute sum.
#
For 2-Norm: Use the function np.linalg.norm(matrix, 2) to calculate the largest singular value (spectral norm).
#
For Infinity Norm: Use the function np.linalg.norm(matrix, np.inf) to calculate the row-wise maximum absolute sum.
# Step 4: 
Print the result of each norm (formatted to 2 decimal places for 2-Norm if needed).
# Step 5: 
End the program.
## Program:
```Python
# 1-Norm of a Matrix
#Name: K.SRISARAN KARTHIK
#Register Number: 212224230275
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)



# 2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: K.SRISARAN KARTHIK
#RegisterNumber: 212224230275


import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))




# Infinity Norm of a Matrix
#Name: K.SRISARAN KARTHIK
#Register Number: 212224230275
import numpy as np
matrix=np.array(eval(input()))
res=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(res))




```
## Output:
### 1-Norm of a Matrix
![EXP 7 SS1](https://github.com/user-attachments/assets/62054b43-f59e-4fbe-b237-808a1af32fe4)

### 2-Norm of a Matrix
![EXP 7 SS2](https://github.com/user-attachments/assets/a8a2e47f-6ffa-4eea-b397-2e34d01b2b8e)


### Infinity Norm of a Matrix
![EXP 7 SS3](https://github.com/user-attachments/assets/86ff18e3-93a1-4f5f-ada7-44d67aef4c94)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
