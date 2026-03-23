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
# Register No:25013757
# Developed By:s syed suhaib

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)


# 2-Norm of a Matrix
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix

<img width="793" height="207" alt="image" src="https://github.com/user-attachments/assets/e6d46744-eeea-4c07-80b0-d7e5851c9e52" />

### 2-Norm of a Matrix
<img width="795" height="377" alt="image" src="https://github.com/user-attachments/assets/e386d346-f257-41d1-96c7-22a242bf2d10" />

### Infinity Norm of a Matrix
<img width="441" height="180" alt="image" src="https://github.com/user-attachments/assets/4b2e66a3-3041-4348-80f7-a923df8814df" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
