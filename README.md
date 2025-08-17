# TASK-1-AND-TASK-2-Factorial-Using-a-Function-AND-Using-the-Math-Module-for-Calculations

Task 1: Calculate Factorial Using a Function 


def factorial(n):

    if n == 0 or n == 1:
        return 1
    else:
        return n * (factorial(n-1))

num = int(input("Enter a number: "))
print("Factorial is:",factorial(num))

Task 2: Using the Math Module for Calculations

import math

number = float(input("Enter a number: "))

print("Square root:",math.sqrt(number))

print("Natural logarithm:",math.log(number))

print("Sine (radians):",math.sin(number))
