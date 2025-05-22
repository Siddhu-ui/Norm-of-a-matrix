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
# Register No:  212224040317
# Developed By: SIDDHARTH S

```

```
Python
# 1-Norm of a Matrix
import numpy as np

a=np.array(eval(input()))

norm = np.linalg.norm(a,1)

print(norm)

# 2-Norm of a Matrix
import numpy as np

a = np.array(eval(input()))

norm = np.linalg.norm(a,2)

print(f"{norm:.2f}")

# Infinity Norm of a Matrix
import numpy as np

a=np.array(eval(input()))

norm = np.linalg.norm(a,np.inf)

print(f"{norm:.2f}")
```


## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/7cbaa9dd-b5ce-4c0b-8f0f-bdda9410899e)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/fcb55bca-ec24-4876-9bc1-94bca87a113c)


### 3-Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/1b553973-0a92-4eb8-9d9f-b2094cea2775)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
