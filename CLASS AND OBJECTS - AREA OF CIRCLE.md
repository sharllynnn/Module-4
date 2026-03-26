# Exp.No:4a  
## CLASS AND OBJECTS - AREA OF CIRCLE
---
### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `pen` and function name `stationary`.

---
### ALGORITHM
1. Begin the program.  
2. Create a class named `pen`.  
3. Define a method `stationary(self, r)` inside the class `pen` that accepts a radius `r` as an argument.  
4. Inside the `stationary` method:  
   - Calculate the area of a circle using the formula: Area = π × r²  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `pen` class and store it in the variable `p`.  
7. Call the `stationary` method of the `pen` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
import math
class pen:
    def stationary(self, r):
        area = math.pi * r ** 2
        print("Area of circle:", round(area, 2))

r = int(input())
p = pen()
p.stationary(r)
```

### OUTPUT
<img width="515" height="162" alt="image" src="https://github.com/user-attachments/assets/f67ad4b4-a0e9-4071-8e6b-26598da1f688" />


### RESULT
Thus, the Python program to find the area of a circle using class name `pen` and function name `stationary` has been successfully executed and the output is verified.
