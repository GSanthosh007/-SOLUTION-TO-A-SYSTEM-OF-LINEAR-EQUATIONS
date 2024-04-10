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
#Developed by: SANTHOSH G
#RegisterNumber:212223240152
import numpy as np
A = np.array([[1, -3],[3, 1]])
B = np.array([0,10])
result=np.linalg.solve(A, B)
print(result)
```

## Output:
![Screenshot 2024-04-10 204845](https://github.com/GSanthosh007/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/147527586/d7a34e72-b1e4-4b5a-8852-e5dc14b5c50e)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

