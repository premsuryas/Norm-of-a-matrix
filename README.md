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
Python
# Register No:
# Developed By:
# 1-Norm of a Matrix
```
import numpy as np
def calculate_1norm(matrix):
    norm1=np.linalg.norm(matrix,ord=1)
    return round(norm1,2)
matrix=eval(input())
result=calculate_1norm(matrix)
print(f"{result:.2f}")

```





# 2-Norm of a Matrix
```
import numpy as np
matrix=eval(input())
norm2=np.linalg.norm(matrix,ord=2)
print(f"{norm2:.2f}")

```




# Infinity Norm of a Matrix
```
import numpy as np
a=eval(input())
norm=np.linalg.norm(a,ord=np.inf)
print(f"{norm:.2f}")

```





```
## Output:
### 1-Norm of a Matrix
file:///home/sec/Norm-of-a-matrix/Screenshot%20from%202023-12-27%2019-59-06.png




### 2-Norm of a Matrix
![Screenshot from 2023-12-27 20-00-05](https://github.com/premsuryas/Norm-of-a-matrix/assets/147473858/8b613c15-a765-41b1-a07d-d9e9b5fed957)



### Infinity Norm of a Matrix
![Screenshot from 2023-12-27 20-00-45](https://github.com/premsuryas/Norm-of-a-matrix/assets/147473858/c0d3de3b-9714-4331-9936-921c7661765a)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
