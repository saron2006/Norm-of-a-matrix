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
# Register No:212223230197
# Developed By:SARON XAVIER A
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/saron2006/Norm-of-a-matrix/assets/138849343/fb7d2b34-59ad-4695-a638-6f00ff336022)


### 2-Norm of a Matrix

![image](https://github.com/saron2006/Norm-of-a-matrix/assets/138849343/a7ca3cb0-8c0f-47e5-8d28-673d213243f5)

### Infinity Norm of a Matrix
![image](https://github.com/saron2006/Norm-of-a-matrix/assets/138849343/0a18f4e3-6f91-4f62-a1ef-af9897b5a1d8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
