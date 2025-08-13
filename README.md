# Assignment-1
# Task 1: Perform Basic Mathematical Operations

# 1. Take two numbers as input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# 2. Perform the basic arithmetic operations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2
division = num1 / num2 if num2 != 0 else "Undefined (division by zero)"

# 3. Display the results
print(f"Addition: {addition}")
print(f"Subtraction: {subtraction}")
print(f"Multiplication: {multiplication}")
print(f"Division: {division}")

#Task 2: Create a Personalized Greeting
Assigl# Take user's first name as input
first_name = input("Enter your first name: ")

# Take user's last name as input
last_name = input("Enter your last name: ")

# Concatenate first name and last name into full name
full_name = first_name + " " + last_name

# Print personalized greeting
print(f"Hello, {full_name}! Welcome to the Python program.")
