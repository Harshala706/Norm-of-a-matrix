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
# Register No:212224040050
# Developed By:B Harshala Reddy
 **1-Norm of a Matrix**
'''
Program to find 1-norm of a matrix.
Developed by:B Harshala Reddy
RegisterNumber: 212224040050
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)

** 2-Norm of a Matrix**
'''
Program to find 2-norm of a matrix.
Developed by:B Harshala Reddy
RegisterNumber: 212224040050
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))

** Infinity Norm of a Matrix**

'''
Program to find Infinity-norm of a matrix.
Developed by:B Harshala Reddy
RegisterNumber: 212224040050
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))

```
## Output:
### 1-Norm of a Matrix
<img width="1229" height="788" alt="Screenshot 2025-09-29 232034" src="https://github.com/user-attachments/assets/fedb23b7-46a2-4489-b477-58639f67ce94" />

### 2-Norm of a Matrix
<img width="1212" height="780" alt="Screenshot 2025-09-29 232050" src="https://github.com/user-attachments/assets/c7a4df9a-e08e-4715-8f88-98cbfb089b65" />

### Infinity Norm of a Matrix
<img width="1058" height="741" alt="Screenshot 2025-09-29 232104" src="https://github.com/user-attachments/assets/71a22d5a-48cd-4e38-9e0b-d606976d0682" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
