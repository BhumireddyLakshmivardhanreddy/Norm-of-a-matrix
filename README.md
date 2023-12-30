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
# Register No:23009662
# Developed By:BHUMIREDDY LAKSHMI VARDHAN REDDY
# 1-Norm of a Matrix
program to find 1-norm of a matrix.
Developed by:BHUMIREDDY LAKSHMI VARDHAN REDDY
RegisterNumber:212223240016
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: BHUMIREDDY LAKSHMI VARDHAN REDDY
RegisterNumber: 212223240016
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
# Infinity Norm of a Matrix
Program to find Infinity norm of a matrix.
Developed by: BHUMIREDDY LAKSHMI VARDHAN REDDY
RegisterNumber: 212223240016
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![NORM1](https://github.com/BhumireddyLakshmivardhanreddy/Norm-of-a-matrix/assets/148514637/64bf6ae4-3343-4197-a80c-a0e50c0ed6bf)
### 2-Norm of a Matrix
![NORM2](https://github.com/BhumireddyLakshmivardhanreddy/Norm-of-a-matrix/assets/148514637/717c02d6-d023-4148-8117-fc3adcdef680)
### Infinity Norm of a Matrix
![NORM](https://github.com/BhumireddyLakshmivardhanreddy/Norm-of-a-matrix/assets/148514637/57dc4e98-d055-4c24-8e75-313f57dd9ee0)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
