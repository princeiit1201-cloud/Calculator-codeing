# Calculator-codeing
#This is my first code in class 12 in python programming.
def calculator():
    print("Simple Calculator")
    print("Operations: +  -  *  /")

    num1 = float(input("Enter first number: "))
    op = input("Enter operator (+, -, *, /): ")
    num2 = float(input("Enter second number: "))

    if op == "+":
        print("Result:", num1 + num2)
    elif op == "-":
        print("Result:", num1 - num2)
    elif op == "*":
        print("Result:", num1 * num2)
    elif op == "/":
        if num2 != 0:
            print("Result:", num1 / num2)
        else:
            print("Error: Cannot divide by zero")
    else:
        print("Invalid operator")

calculator()
