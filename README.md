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
# Register No: 212224240108
# Developed By: Omkar Varma S
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat= np.array(eval(input())) 
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
A = np.array(eval(input()))
inf_norm = np.linalg.norm(A, np.inf)
print(f"{inf_norm:.2f}")



```
## Output:
### 1-Norm of a Matrix

<img width="1242" height="1008" alt="image" src="https://github.com/user-attachments/assets/d3f81f99-64dd-4a03-b1e3-2f136e791599" />


### 2-Norm of a Matrix

<img width="1290" height="987" alt="image" src="https://github.com/user-attachments/assets/dd45203a-4ed6-49d0-a646-0a7216be7e64" />


### Infinity Norm of a Matrix

<img width="1254" height="984" alt="image" src="https://github.com/user-attachments/assets/31be5a97-8c2e-40e5-be36-ad787c0fc188" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
