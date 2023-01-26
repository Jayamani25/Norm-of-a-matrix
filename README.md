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
# Register No: 22008124
# Developed By: JAYAMANI R
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
# Register No: 22008124
# Developed By: JAYAMANI R
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
# Register No: 22008124
# Developed By: JAYAMANI R

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![1](https://user-images.githubusercontent.com/85949888/214760783-44ed201a-cd01-49c9-b243-92decd908d0d.png)


### 2-Norm of a Matrix
![2](https://user-images.githubusercontent.com/85949888/214760901-83945bcf-179a-4547-9a0f-adf1cfa21847.png)


![3](https://user-images.githubusercontent.com/85949888/214760992-fec671ed-c4f2-4af3-9064-55342ceaea43.png)
### Infinity Norm of a Matrix


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
