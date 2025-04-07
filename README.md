# PYTHON-ASSIGNMENT
# Basic Calculator Program

# Function to perform the desired operation
def calculate(num1, num2, operator):
    if operator == "+":
        return num1 + num2
    elif operator == "-":
        return num1 - num2
    elif operator == "*":
        return num1 * num2
    elif operator == "/":
        if num2 != 0:
            return num1 / num2
        else:
            return "Error! Division by zero."
    else:
        return "Invalid operator!"

# Ask user for input
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operator = input("Enter the operation (+, -, *, /): ")

# Perform calculation and display the result
result = calculate(num1, num2, operator)
print(f"The result of {num1} {operator} {num2} = {result}")




