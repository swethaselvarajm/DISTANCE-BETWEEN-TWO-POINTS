### EXP 1C:DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points.
## ALGORITHM:

### Step 1: 
Import the math module.

### Step 2: 
Get the first point(x1,y1) and second point(x2,y2) in form of list.

### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)

### Step 4: 
Calculate the distance using the sqrt() function.

### Step 5: 
Print the result.

### PROGRAM:
 ```
#Program to find the distance between two points.
#Developed by: SWETHA.S
#RegisterNumber:212222230155

import math
l1=[4,2]
l2=[10,6]
d=math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print('{:.2f}'.format(d)) 
```

### OUTPUT:
![PYTHON](https://github.com/swethaselvarajm/DISTANCE-BETWEEN-TWO-POINTS/assets/119525603/ca1fe90c-8596-4850-b610-0b0196b6e746)


### RESULT:
Thus the distance between two points is calculated using python program.
