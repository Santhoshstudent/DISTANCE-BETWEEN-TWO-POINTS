# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
### Step 2: 
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
### Step 5: 
### PROGRAM:
#Program to find the distance of the bridge from one point to another point
#Developed by:Santhosh kumar B
#Register no:212223230193
import math
def calculate_distance(point1, point2):
    x1, y1 = point1
    x2, y2 = point2
    distance = math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2)
    return distance
point1 = [4, 2]
point2 = [10, 6]
distance = calculate_distance(point1, point2)
print(f"{distance:.2f}")
  


### OUTPUT:
![image](https://github.com/Santhoshstudent/DISTANCE-BETWEEN-TWO-POINTS/assets/145446853/cdcb284a-c742-4ae8-8f90-d06aa12660d7)



### RESULT:
