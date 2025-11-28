# python_Assignments_1
🐍 Python Assignments – Basic Programs

This repository contains two beginner-friendly Python programs designed to practice user input, string handling, and basic arithmetic operations. Each program includes a description, code, and example usage.

📘 Program 1: Basic Arithmetic Operations

This program takes two numbers as input from the user and performs:

1. Addition
2. Subtraction 
3. Multiplication 
4. Division (rounded to 2 decimal places)

📄 Code
# Perform Basic Operations like addition, subtraction, multiplication, divide by taking two number as user input
num1=float(input("Enter the first number: "))
num2=float(input("Enter the second number: "))

Addition=int(num1)+int(num2)
Subtraction=int(num1)-int(num2)
Multiplication=int(num1)*int(num2)
Division=int(num1)/int(num2)

print("Addition: ",Addition)
print("Subtraction: ",Subtraction)
print("Multiplication: ",Multiplication)
print("Division: ",round(Division,2))

🖥️ Example Output
Enter the first number: 5
Enter the second number: 3
Addition:  8
Subtraction:  2
Multiplication:  15
Division:  1.67

📘 Program 2: User Greeting Program

This program asks the user to enter their first name and last name.
It then prints a friendly greeting message.

📄 Code
user_first_name = input("Enter your first name: ")
user_last_name = input("Enter your last name: ")

print("Hello, ", user_first_name, user_last_name, "! Welcome to the Python program.")

🖥️ Example Output
Enter your first name: Rahul
Enter your last name: Sharma
Hello,  Rahul Sharma ! Welcome to the Python program.

▶️ How to Run the Programs

Make sure you have Python 3 installed.

Clone the repository:

git clone https://github.com/shy1505/python_Assignments_1.git


Navigate to the folder:

cd python_Assignments_1


Run any program:

python assignment_1.py


or

python assignment_1b.py




📄 License

This project is open-source. Feel free to modify and use the code for learning or assignments.