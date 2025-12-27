# Norm of a matrix

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. **Start the program.**
2. **Import** the `numpy` library as `np`.
3. **Read the matrix** elements using `eval(input())` and store them in `mat`.
4. **Compute the 1-Norm** using `np.linalg.norm(mat, 1)`.
5. **Format the result** to two decimal places.
6. **Display the 1-Norm** of the matrix.
7. **End the program.**
   
   ---

## **Part B – L2-Norm of a Matrix**

1. **Start the program.**
2. **Import** the `numpy` library as `np`.
3. **Input the matrix** and store it in `mat`.
4. **Find the L2-Norm** using `np.linalg.norm(mat, 2)`.
5. **Round or format** the result to two decimal places.
6. **Print the L2-Norm** of the matrix.
7. **End the program.**
   
   ---

## **Part C – Infinity Norm of a Matrix**

1. **Start the program.**
2. **Import** the `numpy` library as `np`.
3. **Read the matrix** from user input.
4. **Calculate the Infinity Norm** using `np.linalg.norm(mat, np.inf)`.
5. **Format** the result to two decimal places.
6. **Display** the Infinity Norm of the matrix.
7. **End the program.**


## Program:
```
# Register No: 25008604
# Developed By: MIthun Sai P

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
noem_of_matrix="{:.2f}".format(ans)
print(noem_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="869" height="564" alt="image" src="https://github.com/user-attachments/assets/b480f12d-b6c6-432b-ad87-7a52512e72db" />
<img width="875" height="236" alt="image" src="https://github.com/user-attachments/assets/d207b0b1-c32f-4321-b27f-1e97b602d74d" />


### 2-Norm of a Matrix
<img width="869" height="589" alt="image" src="https://github.com/user-attachments/assets/a7dfb332-11d5-43f1-88b5-dccf8e0a394e" />
<img width="886" height="279" alt="image" src="https://github.com/user-attachments/assets/0d34113f-64e7-420c-b468-b9c8e247ba2f" />


### Infinity Norm of a Matrix
<img width="884" height="572" alt="image" src="https://github.com/user-attachments/assets/7c28368f-df5d-41c9-b639-ecb3a7f6f56c" />
<img width="881" height="248" alt="image" src="https://github.com/user-attachments/assets/6c968236-f235-4dc9-9c58-1653d34f2c8d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
