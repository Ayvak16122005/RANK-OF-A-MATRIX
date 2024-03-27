# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:we have to intialise program using import numpy to perform mathematical calculation
### Step 2:THe input from the user is stored in the variable a
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:  end of the program

## QUESTION:
```
Write a program to find the rank for the given matrix([5,-3,-10],[2,2,-3],[-3,-1,5]).
`````
## Program:
```
/*
Program to implement univariate Linear Regression to fit a straight line using least squares.
Developed by:Kavya T 
RegisterNumber:2305003004  
*/
`````
`````python
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
`````
## Output:
![Screenshot 2024-03-27 212420](https://github.com/Ayvak16122005/RANK-OF-A-MATRIX/assets/147690197/92fb5cd8-70d4-4ded-a7a7-6ab5374da541)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

