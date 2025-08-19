# SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: YOGESH D
#Register Number: 212224040371
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
c=np.linalg.solve(A,B)
print(c)
```

## Output:
<img width="1312" height="937" alt="image" src="https://github.com/user-attachments/assets/0ccbda4c-b577-4dd9-bace-7354f46fb803" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

