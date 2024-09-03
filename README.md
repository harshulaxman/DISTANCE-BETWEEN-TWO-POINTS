# DATE:
# EXP-3: DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
 
### PROGRAM:
```
# Developed by: harsshitha lakshamanan
# Register no:212223230075
import math

def calculate_distance(x1, y1, x2, y2):
    distance = math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2)
    return round(distance, 2)

x1, y1 = 4, 2
x2, y2 = 10, 6
distance = calculate_distance(x1, y1, x2, y2)
print(distance)
```


### OUTPUT:
![image](https://github.com/user-attachments/assets/fb6beb52-7308-4548-a24c-dfe8acab92a1)

![image](https://github.com/user-attachments/assets/abe86300-da7f-4c6a-a4c7-690c605fa592)

### RESULT:
