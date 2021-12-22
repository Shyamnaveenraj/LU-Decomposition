# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.start 
2.declare the value  
3.print 
4.stop 

## Program:
```import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

/*
Program to find the LU Decomposition of a matrix.
Developed by:M.Shyam Naveen Raj 
RegisterNumber:21005660 
*/
```

## Output:
![lu decomposition](maths1.jpg)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.start 
2.declare the value  
3.print 
4.stop 

## Program:
```import numpy as np
import scipy
from scipy.linalg import lu_factor,lu_solve
A=([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=([4, 5, 7])
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)



/*
Program to find the LU Decomposition of a matrix.
Developed by:M.Shyam Naveen Raj 
RegisterNumber:21005660 
*/
```

## Output:
![lu decomposition](maths2.jpg)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

