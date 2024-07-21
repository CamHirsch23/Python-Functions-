def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    try:
        return a / b
    except ZeroDivisionError as e:
        print("Error: Cannot divide by zero")
        return 0

print("Welcome to the Calculator App!")

while True:
    print("Please select an operation:")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Exit")

    operation = input("Enter the number corresponding to the operation: ")

    if operation == "5":
        print("Thank you for using the Calculator App!")
        break

    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))

    if operation == "1":
        result = add(num1, num2)
        print("The result of addition is:", result)
    elif operation == "2":
        result = subtract(num1, num2)
        print("The result of subtraction is:", result)
    elif operation == "3":
        result = multiply(num1, num2)
        print("The result of multiplication is:", result)
    elif operation == "4":
        result = divide(num1, num2)
        print("The result of division is:", result)
    else:
        print("Invalid operation. Please try again.")
