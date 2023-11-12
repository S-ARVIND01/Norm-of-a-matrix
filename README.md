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
# Register No: ARVIND S
# Developed By: 212222240012
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,1)
norm="{:.2f}".format(sol)
print(norm)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,2)
norm="{:.2f}".format(sol)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
sol=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(sol)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-11-12 202059](https://github.com/S-ARVIND01/Norm-of-a-matrix/assets/118707337/173f8231-58f2-408c-8984-1c3dbfa86d87)

### 2-Norm of a Matrix
![Screenshot 2023-11-12 202120](https://github.com/S-ARVIND01/Norm-of-a-matrix/assets/118707337/de6146f9-6a3b-4a08-89ae-29c18475e86c)

### Infinity Norm of a Matrix
![Screenshot 2023-11-12 202142](https://github.com/S-ARVIND01/Norm-of-a-matrix/assets/118707337/2f24c4b5-1afd-4049-bb87-b9e495c992f1)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
