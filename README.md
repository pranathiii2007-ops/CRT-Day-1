CRT Day - 1: Python Basics
Overview

On Day 1 of my Campus Recruitment Training (CRT), I learned the fundamentals of Python programming, including basic syntax, variables, conditional statements, loops, and problem-solving logic.

Topics Covered
Introduction to Python
Variables and data types
Taking user input using input()
Displaying output using print()
Type conversion using int() and float()
Operators in Python
Conditional statements (if, elif, else)
Loops:
for loop
range() function
Basic problem-solving techniques
Programs Practiced
Checking whether a number is even or odd
Checking whether a number is positive, negative, or zero
Finding the largest of two or three numbers
Checking whether a number is prime
Printing prime numbers within a range
Finding the sum of natural numbers
Calculating the factorial of a number
Reversing a number
Checking whether a number is a palindrome
Generating multiplication tables
Solving basic mathematical and logical problems
Key Learning: Prime Number Logic

A prime number is a number greater than 1 that has exactly two factors: 1 and itself.

n = int(input("Enter a number: "))

if n < 2:
    print("Not Prime")
else:
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime")

Learning Outcome
Understood Python fundamentals and syntax.
Learned how to use conditional statements and for loops.
Practiced writing logical solutions for basic programming problems.
Improved problem-solving skills through number-based programs.
Conclusion

Day 1 helped me build a strong foundation in Python programming and introduced me to the logical thinking required to solve coding problems. I will continue practicing and improving my programming skills throughout the CRT sessions.

#Python #CRT #Day1 #Programming #ProblemSolving
