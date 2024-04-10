# EXPERIMENT : 1
# SOLUTION TO A SYSTEM OF LINEAR EQUATIONS
## NAME: AVINASH T
## REG NO: 212223230026
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
```c
#Program to find the solution for the given linear equations.
#Developed by: AVINASH T
#RegisterNumber: 212223230026
import numpy as np
a = np.array([[1,3],[2,5]])
b = np.array([5,-3])
A=np.linalg.solve(a,b)
print(A)
```
![image](https://github.com/AVINASH05T/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/151514286/f1010e7a-6faf-4350-a5d7-709cd4f8878a)
## Output:
![image](https://github.com/AVINASH05T/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/151514286/51cb7e33-f814-47bc-90ab-4cf1b3378fa3)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

