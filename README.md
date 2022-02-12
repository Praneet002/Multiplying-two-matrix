# Multiplying-two-matrix

## AIM:
To write a python program for Multiplying two matrices.

## ALGORITHM:

### Step 1:
Start python program.

### Step 2:
Import numpy.create two null lists.

### Step 3:
Get two matrices from the user using append.

### Step 4:
Multiply the two matrices.

### Step 5:
Display the result.


## PROGRAM: 
```
import numpy as np
mat=int(input())
l1,l2=[],[]
for i in range(mat):
    l1.append(int(input()))
for i in range(mat):
    l2.append(int(input()))
A=np.array(l1)
A2=np.array(l2)
arr=A*A2
print("Product of two arrays is:",arr)
```

## OUTPUT:
![output](https://github.com/Praneet002/Multiplying-two-matrix/blob/main/Multiplying%20Two%20Matrix.png)

## RESULT:
Thus the multiplication of matrix is done
