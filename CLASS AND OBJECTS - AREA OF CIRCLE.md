# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
class saveetha:
    def __init__(self,r):
        self.radius = r
        self.a = 3.141592*r**2
    def get_area(self):
        return self.a
        
r = int(input(""))
b = saveetha(r)
print(f"Area of circle: {b.get_area():.2f}")


```

### OUTPUT
![image](https://github.com/user-attachments/assets/e2f895e8-628b-4f77-8ed0-ec1658e91a51)

### RESULT
Thus the program CLASS AND OBJECTS - AREA OF CIRCLE have been executed and verified sucessfully


