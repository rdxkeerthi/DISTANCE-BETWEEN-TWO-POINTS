# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1:
import the math module
### Step 2: 
Assign the value of the variable
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Print the distance
### Step 5: 
End the program
### PROGRAM:
  ```
#Program to find the distance between two points.
#Developed by: KEERTHIVASAN M
#RegisterNumber:212223100021

import math

def distance(x1, y1, x2, y2):
    return math.sqrt((x2 - x1)**2 + (y2 - y1)**2)

# Coordinates of the first point
x1, y1 = 4, 2

# Coordinates of the second point
x2, y2 = 10, 6

# Calculate the distance
d = distance(x1, y1, x2, y2)

# Print the distance with 2 decimal points
print(" {:.2f}".format(d))

```


### OUTPUT:


### RESULT:
Thus Distance between two points executed successfully
