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
# Register No:212224100008
# Developed By:DASHVIN S
# 1-Norm of a Matrix
''`
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)




# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: E HEMACHANDRAN
RegisterNumber: 212224230093
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))


# 3-Infinity Norm of a Matrix

'''
Program to find infinity of a matrix.
Developed by: E HEMACHANDRAN
RegisterNumber: 212224230093
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(result)



```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/c900eee6-50ad-476c-90b3-036eb02b2b22)
### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/792f5508-7c8c-4be5-ac19-a256e859b499)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/e344afb6-ac6b-433b-bea9-e1b9a5a55b3f)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
