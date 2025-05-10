# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length  # private attribute
        self.__breadth = breadth  # private attribute

    def display(self):
        # Access private members within the class
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

# Instantiate the object
rect = Rectangle(5, 3)

# Call the display method to show the values of the private attributes
rect.display()


```
## Output
![image](https://github.com/user-attachments/assets/19908e06-8b8e-4250-8006-eca7105e1fd4)

## Result
The code has been executed successfully.
