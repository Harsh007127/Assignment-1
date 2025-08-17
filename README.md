# Assignment-1
 

# Task 1: Perform Basic Mathematical Operations

# 1. Take two numbers as input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# 2. Perform the basic arithmetic operations
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2

if num2 != 0:
    division = num1 / num2
else:
    division = None   # None means no valid result

# 3. Display the results
print("\n--- Results ---")
print("Addition:", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
if division is not None:
    print("Division:", division)
else:
    print("Division: Undefined (cannot divide by zero)")


# Task 2: Create a Personalized Greeting

# Take user's first name as input
first_name = input("\nEnter your first name: ")

# Take user's last name as input
last_name = input("Enter your last name: ")

# Concatenate first name and last name into full name
full_name = first_name + " " + last_name

# Print personalized greeting
print(f"\nHello, {full_name}! Welcome to the Python program.")


