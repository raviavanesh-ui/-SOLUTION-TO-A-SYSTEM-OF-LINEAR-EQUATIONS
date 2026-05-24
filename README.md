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
#Developed by: avanesh.r
#RegisterNumber:212225240018
import numpy as np

# Coefficient matrix
A = np.array([[1, 3],
              [2, 5]])

# Constant matrix
B = np.array([5, -3])

# Solve the system
solution = np.linalg.solve(A, B)

print(solution)
```
## Output:

<img width="1229" height="781" alt="Screenshot 2026-05-14 103427" src="https://github.com/user-attachments/assets/4b5e5891-56ca-4ff7-ba94-bc1e487cda3a" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

