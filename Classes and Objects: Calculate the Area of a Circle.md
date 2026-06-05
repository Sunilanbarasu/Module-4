# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `Circle` and a method `area` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```python3
import math
class Circle:
    def __init__(self,radius):
        self.radius=radius
    def area(self):
        return math.pi *self.radius*self.radius
r=float(input())        
C=Circle(r)        
print("Area of circle: {:.2f}".format(C.area()))
    
```
## Output
<img width="1362" height="804" alt="image" src="https://github.com/user-attachments/assets/c78e47ae-9611-4319-9062-aaa5ec856a06" />

## Result
Thus the python  program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `Circle` and a method `area` to perform the calculation is completed successfully.
