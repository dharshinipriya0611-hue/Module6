# Exp.No:26  
## Method Overriding

---

### AIM  
To write a Python program to demonstrate polymorphism by creating two classes India and USA with the same method names (capital(), language(), and type()) and then accessing them using a common interface.

---

### ALGORITHM

1. Start the program.
2. Define the class India with methods capital(), language(), and type().
3. Define the class USA with the same methods capital(), language(), and type().
4. Create objects obj_ind for the India class and obj_usa for the USA class.
5. Use a for loop to iterate through the objects and call the common methods.
6. Display the output for both countries.
7. End the program.

---

### PROGRAM
~~~
Reg.No: 212223090004
Name: D Dharshini priya

class India():
	def capital(self):
		print("New Delhi is the capital of India.")
	def language(self):
		print("Hindi is the most widely spoken language of India.")
	def type(self):
		print("India is a developing country.")
class USA():
	def capital(self):
		print("Washington, D.C. is the capital of USA.")
	def language(self):
		print("English is the primary language of USA.")
	def type(self):
		print("USA is a developed country.")
obj_ind = India()
obj_usa = USA()
for country in (obj_ind, obj_usa):
    country.capital()
    country.language()
    country.type()
~~~

### OUTPUT
<img width="1058" height="276" alt="image" src="https://github.com/user-attachments/assets/34781c89-de74-4fd5-afe5-f83ca4ad23bb" />




### RESULT
Thus the program is created and verified.
