# Simple-Calculator-Python
A simple calculator program using Python
def add(x,y):
    return x+y
def substract(x,y):
    return x-y
def multiply(x,y):
    return x*y
def divide(x,y):
    return x/y if y!=0 else "Error"

num1 = float(input("Enter first number: "))
operator = input("Enter operator (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if operator == "+":
    print("Result:", add(num1, num2))

elif operator == "-":
    print("Result:", subtract(num1, num2))

elif operator == "*":
    print("Result:", multiply(num1, num2))

elif operator == "/":
    print("Result:", divide(num1, num2))

else:
    print("Invalid operator")
