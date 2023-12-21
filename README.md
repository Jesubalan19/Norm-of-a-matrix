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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Ex 7 i](https://github.com/Jesubalan19/Norm-of-a-matrix/assets/144979294/4ffa12ec-e4d7-4fd3-b6c4-6c911bb4ee4c)

### 2-Norm of a Matrix
![Ex 7 ii](https://github.com/Jesubalan19/Norm-of-a-matrix/assets/144979294/cf6dea4f-c3bb-4c9e-9b8d-dbec905cfe88)

### Infinity Norm of a Matrix
![Ex 7 iii](https://github.com/Jesubalan19/Norm-of-a-matrix/assets/144979294/196a8059-4fa8-40f1-a18c-2f9f2bd8187c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
