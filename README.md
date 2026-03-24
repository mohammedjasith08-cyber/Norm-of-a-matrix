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
# Register No:25011638
# Developed By:MOHAMMED JASITH
# 1-Norm of a Matrix
import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,1)

print(o)



# 2-Norm of a Matrix
import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,2)

print(f"{o:.2f}")



# Infinity Norm of a Matrix
import numpy as np

i=np.array(eval(input()))

o=np.linalg.norm(i,np.inf)

print(o)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/5d29bc20-8b02-4c6c-8086-59501ea66a4c" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/4b57c2d5-aad2-49e5-8008-1f720ddd550f" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1282" height="368" alt="image" src="https://github.com/user-attachments/assets/dd536119-3acf-42dd-9493-40dcb7aaaf5d" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
