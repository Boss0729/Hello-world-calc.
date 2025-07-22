# Hello-world-and-basis-calculator

# Aim: To print Hello World and design a Claculator to add,subtract,multiply and divide two user input number.

# Apparatus: VS Code or Programiz online compiler

# Theory:
This C++ program brings together two basic concepts to help beginners get started: displaying output and performing simple calculations. It starts by including the iostream library, which allows the use of `cin` and `cout` for input and output. Inside the `main()` function, it first prints a welcome message like “Hello World” to the screen using `cout`. Then, it moves on to a calculator section, where it asks the user to enter two floating-point numbers. These numbers are stored in variables and used to perform addition, subtraction, multiplication, and division. Each result is displayed on the screen, and because the program uses the `float` data type, it handles decimal values accurately. The program finishes with `return 0;` to indicate successful execution. Altogether, this example demonstrates the basics of C++ syntax, input/output handling, and arithmetic operations in a clear and beginner-friendly way.

# About iostream and std
The main purpose of iostream is to give the programmer a basic method of input/output using cin and cout. The identifiers cin and cout reside in a namespace called std. The programmer has two options to use them: Using std:: in front of the identifiers (for example, std::cout) or using using namespace std; which removes the requirement to prefix std::.

Program Explaination: Algorithm

Start the program.
Display a welcome message:
Output: Welcome to C++ Programming!
Output: Hello World
Prompt the user to enter an integer: -Output: Enter a number: -Input: User enters an integer value and it is stored in variable x -Output: You entered: x

Calculator functionality: Prompt the user to input two numbers:

Output: Enter number 1: → Input stored in variable a
Output: Enter number 2: → Input stored in variable b
Perform operations: sum = a + b sub = a - b mul = a * b div = a / b

Display results:

Output: Sum: sum
Output: Subtraction: sub
Output: Multiplication: mul
Output: Division: div
End the program.
The program then prints each of the calculations in the format of "Sum:" followed by std::endl to print the result of the calculation on a new line. We conclude with return 0; which indicates successful execution of our program.

Conclusion: This Program will help in understaing of basic input and output, diffrent arithmetic operation in C++ and will give short idea on how we can built programs in C++.
