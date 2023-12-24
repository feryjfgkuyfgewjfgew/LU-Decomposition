# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: naresh.r
RegisterNumber: 23005559
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: naresh.r
RegisterNumber: 23005559
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:

![Screenshot 2023-12-24 173223](https://github.com/feryjfgkuyfgewjfgew/LU-Decomposition/assets/150319377/003eaeb1-e11b-4f42-9cea-2f7e44b50ab2)

![Screenshot 2023-12-24 173355](https://github.com/feryjfgkuyfgewjfgew/LU-Decomposition/assets/150319377/41542a6f-abad-41aa-b9eb-2600f8d58885)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

