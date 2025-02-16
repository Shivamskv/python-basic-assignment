# python-basic-assignment
QUESTION :-Explain the key features of Python that make it a popular choice for programming.
Ans:-Python is one of the most popular programming languages due to its simplicity, versatility, and efficiency. Here are some key features that make Python a top choice for developers.
QUESTON :-Describe the role of predefined keywords in Python and provide examples of how they are used in a program.
Ans:-Predefined keywords in Python are reserved words that have special meanings and cannot be used as variable names, function names, or any other identifiers. These keywords define the syntax and structure of Python programs.
Python has 35+ keywords (varies by version), including control statements, logical operators, and function-related keywords.
QUESTION :-Compare and contrast mutable and immutable objects in Python with examples.
ANS:-🔹 Comparison: Mutable vs. Immutable Objects in Python
In Python, objects are categorized into mutable (can be changed after creation) and immutable (cannot be changed after creation).

Feature	Mutable Objects	Immutable Objects
Can be modified?	✅ Yes	❌ No
Memory location change?	❌ No (same object is modified)	✅ Yes (new object is created)
Examples	list, dict, set, bytearray	int, float, str, tuple, frozenset, bool, bytes
QUESTION:-Discuss the different types of operators in Python and provide examples of how they are used.
ANS:-Operators in Python are symbols that perform operations on variables and values. Python has several types of operators:

Operator Type	Description	Example Operators
Arithmetic Operators	Perform mathematical operations	+, -, *, /, //, %, **
Comparison Operators	Compare values	==, !=, >, <, >=, <=
Logical Operators	Combine conditional statements	and, or, not
Bitwise Operators	Work at the bit level	&, `
Assignment Operators	Assign values to variables	=, +=, -=, *=, /=, //=, %=
Identity Operators	Check object identity	is, is not
Membership Operators	Check for membership in a sequence	in, not in
QUESTION:-Explain the concept of type casting in Python with examples.
ANS:-Type casting (or type conversion) is the process of converting one data type into another. Python provides two types of type casting:
#fImplicit Type Casting (Automatic Conversion)
Explicit Type Casting (Manual Conversion)
QUESTION:-How do conditional statements work in Python? Illustrate with examples.
ANS:-Conditional statements allow a program to make decisions based on conditions.
They control the flow of execution using if, elif, and else.
#if:- age = 18

if age >= 18:
    print("You are eligible to vote.")  # This runs if the condition is True
#elif:-marks = 85

if marks >= 90:
    print("Grade: A")
elif marks >= 75:
    print("Grade: B")
elif marks >= 50:
    print("Grade: C")
else:
    print("Grade: F")
QUESTION:- Describe the different types of loops in Python and their use cases with examples.
Ans:-Loops allow executing a block of code multiple times. Python provides two types of loops:
for loop – Iterates over a sequence (e.g., list, string, range).
while loop – Repeats as long as a condition is True.
#for loop:-fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
#for While loop:-x = 1
while x <= 5:
    print(x)
    x += 1  # Increment x

