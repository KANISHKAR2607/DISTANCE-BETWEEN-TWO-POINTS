# DISTANCE-BETWEEN-TWO-POINTS

## AIM:

To write a python program to find the distance two 2 points

## ALGORITHM:

### Step 1: 
Import the math module to use the built-in functions for calulations
### Step 2: 
Enter the coordinates of point one and two in the input
### Step 3: 
Substitute the values in the distance formula  ![](/formula.jpg)
### Step 4: 
Print the distance using the formula
### Step 5: 
End the program

### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Kanishkar
#RegisterNumber: 22007816
import math 
l1 = [4,2]
l2 = [10,6]
d = math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(d))
```

### OUTPUT:
![](distancebetweentwopoints.png)

### RESULT:
Thus the program for calculating the distance between two points are succesfully executed.
