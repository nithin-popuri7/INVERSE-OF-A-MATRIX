# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation 
### Step 2: 
Prepare the lists from each inverse of matrix and assign in np.array()
### Step 3:
Using the np.linalg.sol(), we can find the solutions.

### Step 4:
end the program 

## Program:
~~~
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
sol=np.linalg.solve(A,B)
print(sol)
~~~
## Output:
![github logo](/kl.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

