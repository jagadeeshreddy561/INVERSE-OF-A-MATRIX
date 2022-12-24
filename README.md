# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use built-infunctions for calculation
### Step 2: 
Prepare the lists from each linear equations and ssign in np.array{}
### Step 3: 
Using the np.linalg solve(),we can find the solutions.
### Step 4: 
End the program
## Program:
```python
#Program to find the inverse of a matrix.
#Developed by: jagadeesh
#RegisterNumber:22001910
import numpy as np
A = np.array([[2,1,1],[1,1,1],[1,-1,2]])
B = np.linalg.inv(A)
print(B)

```
## Output:
![MODEL](/Screenshot%20from%202022-12-24%2020-44-51.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

