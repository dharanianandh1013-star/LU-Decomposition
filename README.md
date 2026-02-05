# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```

## Output:
![lu decomposition]()

<img width="931" height="370" alt="Screenshot 2026-02-05 144342" src="https://github.com/user-attachments/assets/582540c6-af2e-4048-a03f-6bbc2f199925" />

<img width="714" height="149" alt="Screenshot 2026-02-05 144348" src="https://github.com/user-attachments/assets/52b4a8f1-c488-4a6b-815d-c5ecd8559730" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

