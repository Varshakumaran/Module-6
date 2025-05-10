# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
# Class Beans
class Beans:
    def type(self):
        print("Vegetable")
    
    def color(self):
        print("Green")

# Class Mango
class Mango:
    def type(self):
        print("Fruit")
    
    def color(self):
        print("Yellow")

# Generic function
def func(obj):
    obj.type()
    obj.color()

# Create objects
beans = Beans()
mango = Mango()

# Call the generic function
func(beans)  # This will call the Beans class methods
func(mango)  # This will call the Mango class methods


```
## Output
![image](https://github.com/user-attachments/assets/eff74746-53d6-41d4-a9db-3f27eed24b1a)

## Result
The code has been executed successfully.
