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
# Python program to find the 1-norm, 2-norm and infinity norm of the matrix
# Register No: 212222240037
# Developed By: S.Jaiganesh

# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)

# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![Screenshot (88)](https://github.com/Jaiganesh235/Norm-of-a-matrix/assets/118657189/441a23cd-3451-4940-98fc-b5edadd27eb7)

### 2-Norm of a Matrix
![Screenshot (89)](https://github.com/Jaiganesh235/Norm-of-a-matrix/assets/118657189/26973aff-da81-436e-9346-ffeceea75a29)

### Infinity Norm of a Matrix
![Screenshot (90)](https://github.com/Jaiganesh235/Norm-of-a-matrix/assets/118657189/08eddefa-1723-4b44-bbce-eeb7b2df5529)


## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
