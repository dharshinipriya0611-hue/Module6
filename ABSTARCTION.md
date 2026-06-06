# Exp.No:28  
## Abstraction

---

### AIM 
---
Create the abstract method calculate_area which is of the abstract class 'Shape'. The implementation of this abstract class can be defined in the sub-classes that inherit the class 'Shape'. 'Rectangle' and 'Circle' are the two sub-classes that inherit the abstract class 'Shape'.

### ALGORITHM

1. Start the program.
2. Import ABC and abstractmethod from the abc module.
3. Define an abstract base class Shape with an abstract method calculated_area().
4. Define the Rectangle class inheriting from Shape and implement the calculated_area() method.
5. Define the Circle class inheriting from Shape and implement the calculated_area() method.
6. Display the area of each shape.
7. End the program.

---

### PROGRAM
~~~
Reg.No: 212223090004
Name: D Dharshini priya

from abc import ABC, abstractmethod
class Shape(ABC):
    @abstractmethod
    def calculate_area(self):
        pass
class Rectangle(Shape):
    length = 5
    breadth =3 
    def calculate_area(self):
        return self.length * self.breadth

class Circle(Shape):
    radius = 4
    def calculate_area(self):
        return 3.14*4*4
        
r=Rectangle()
r.calculate_area()
c=Circle()
c.calculate_area()
print("Area of a rectangle:", r.calculate_area())
print("Area of a circle:", c.calculate_area())
~~~


### OUTPUT
<img width="862" height="253" alt="image" src="https://github.com/user-attachments/assets/63ba6574-9070-4feb-9fed-6f226f3906f3" />



### RESULT
Thus the program is created and verified.
