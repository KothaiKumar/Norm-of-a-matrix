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
# Register No: 22006043
# Developed By: Kothai K
# 1-Norm of a Matrix
import numpy as np 

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix=("{:.2f}".format(ans))

print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np

a=np.array(eval(input()))

ans=np.linalg.norm(a,2)

print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
import numpy as np

a=np.array(eval(input()))

ans=np.linalg.norm(a,np.inf)

print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix
![norm_1](https://user-images.githubusercontent.com/121215739/214841212-d6f2c5e1-c756-4578-af68-b014ebdb30f4.png)

### 2-Norm of a Matrix
![norm_2](https://user-images.githubusercontent.com/121215739/214841273-07422b7f-ae21-4a76-8b2f-a4d3e866ff75.png)


### Infinity Norm of a Matrix
![NORM_INF](https://user-images.githubusercontent.com/121215739/214841320-5b7324f5-9816-41a2-9399-cb681bf2dcbe.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
