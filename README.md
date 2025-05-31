# Assignment 1: Basic Python Concepts

## Module: 2 — Python Programming Basics

This repository contains solutions to **Assignment 1** under Module 2. The goal is to demonstrate the use of basic Python input/output operations, arithmetic computations, string manipulation, and console display formatting.

---

## Task 1: Perform Basic Mathematical Operations

### 📌 Problem Statement:
Write a Python program that:
1. Takes two numbers as input from the user.
2. Performs the following mathematical operations:
   - Addition
   - Subtraction
   - Multiplication
   - Division
3. Displays the results of each operation on the screen.
**Sol 1 :** #Takes two numbers as input from the user.
a=input("Enter First Number")
b=input("Enter Second Number")
**Sol 2 and 3 :** # Performs the basic mathematical operations on these two numbers:
#o	Addition
#o	Subtraction
#o	Multiplication
#o	Division
a = int(input("Enter First Number: "))
b = int(input("Enter Second Number: "))
c = a + b
d = a - b
e = a * b
f = a / b  
# Display Result of Each Operations 
print("Addition:", c)
print("Subtraction:", d)
print("Multiplication:", e)
print("Division:", f)
**Expected Output:**
Enter First Number: 10
Enter Second Number: 5
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2.0
## Task 2: Create a Personalized Greeting
Write a Python program that:
1. Takes the user's first and last names as input.
2. Concatenates them into a full name.
3. Prints a personalized greeting message using the full name.
**Sol :** # 1. Take first name and last name as input
first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")

# 2. Concatenate to get full name
full_name = first_name + " " + last_name

# 3. Print personalized greeting
print("Hello, " + full_name + "! Welcome! to the python program")
**Expected Output:**
Enter your first name: Prithvi
Enter your last name: Solanki
Hello, Prithvi Solanki! Welcome! to the python program
