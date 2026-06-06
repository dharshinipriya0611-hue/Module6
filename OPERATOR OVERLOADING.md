# Exp.No:27  
## Operator Overloading

---

### AIM  
write a python program to perform product of two complex number using binary '+' operator overloading class name : complex Ob1 = complex(1, 2) Ob2 = complex(2, 3)

---

### ALGORITHM

1. Start the program.
2. Define a class complex to represent complex numbers.
3. Create a constructor init() to initialize the real part a and imaginary part b.
4. Overload the '+' operator add to add the corresponding real and imaginary parts of two complex numbers and return the complex number in a readable format.
5. Create two objects Obj1 and Obj2 of the complex class with initial values.
6. Print the result.
7. End the program.

---

### PROGRAM
~~~
Reg.No: 212223090004
Name: D Dharshini priya

class Complex:
    def __init__(self,real,imag):
        self.real=real
        self.imag=imag
    def __add__(self,other):
        real_part=self.real*other.real
        imag_part=self.imag*other.imag
        return(real_part,imag_part)
obj1=Complex(1, 2)
obj2=Complex(2, 3)
print(obj1+obj2)
~~~

### OUTPUT
<img width="402" height="216" alt="image" src="https://github.com/user-attachments/assets/883e6a4b-85fd-4c4d-9501-ba1ce2286c11" />

### RESULT
Thus the program is created and verified.

