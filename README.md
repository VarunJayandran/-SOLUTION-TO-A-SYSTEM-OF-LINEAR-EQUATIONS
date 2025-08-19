# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Varun JC
#RegisterNumber:212224240179

import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
c=np.linalg.solve(A,B)
print(c)

```
## Output:

<img width="907" height="345" alt="478867364-f0a8dcd9-d30c-4021-9be4-c35433c2bb3d" src="https://github.com/user-attachments/assets/beff7d30-9982-428c-b951-a3d3f01bcf2a" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

