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
#Developed by: M.Harini
#RegisterNumber:212222240035
import numpy as np
A=np.array ([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
result=np.linalg.solve(A,B)
print(result)
```
## Output:
![Screenshot (2)](https://github.com/Harinimuthu17/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/130278614/0cd0369b-ac8d-40c7-ad01-0489ecdba3a9)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

