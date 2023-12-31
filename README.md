# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

### Step 1
Import the numpy module to use the built-in functions for calculation.

### Step 2
Prepare the lists from each linear equations and assign in np.array().

### Step 3
Using the scipy.linalg and imort lu_fator and lu_solve we get the values.

### Step 4
End the program


## Program:
### To find the L and U matrix
### Program to find L and U matrix using LU decomposition.
### Developed by:HARIHARAN J 
### Register Number: 212223240047
```
import numpy as np
import scipy
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
### To find the LU Decomposition of a matrix
### Program to find the LU Decomposition of a matrix.
### Developed by:HARIHARAN J 
### Register Number: 212223240047
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
#### L and U matrix
![image](https://github.com/HariharanJayavel/LU-Decomposition/assets/144870546/e13c9670-be37-4f30-ad50-84696a75ac0f)

#### LU Decomposition of a matrix
![image](https://github.com/HariharanJayavel/LU-Decomposition/assets/144870546/c538a9f6-412b-416a-9a36-42c2e528a338)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

