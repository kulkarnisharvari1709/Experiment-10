# Experiment-10

Program 1: Swapping Two Numbers Using Call by Reference
Aim:
To implement the concept of call by reference and swap two numbers using reference variables.

Apparatus / Software:
C++ Compiler (e.g., GCC)

Text Editor or IDE (e.g., Code::Blocks, Dev C++, Visual Studio)

Algorithm:
Define a function swap that takes two integers by reference.

Inside the function, use a temporary variable to swap the values.

In the main() function:

Declare and initialize two integer variables a and b.

Call the swap function with a and b as arguments.

Print the values of a and b after the function call.

Conclusion:
This program demonstrates the use of reference variables to modify actual parameters. Since the variables are passed by reference, changes made inside the function reflect in the original variables, successfully swapping their values.

Program 2: Increment Salary Using Call by Reference
Aim:
To demonstrate how call by reference can be used to modify a variable’s value inside a function, specifically for incrementing a salary amount.

Apparatus / Software:
C++ Compiler

Text Editor or IDE

Algorithm:
Define a function increment that takes a reference to an integer (salary).

Increase the salary by 5000 inside the function and print the updated value.

In the main() function:

Declare and initialize an integer sal with 27000.

Print the original salary.

Call the increment function with sal as the argument.

Conclusion:
This program effectively illustrates how call by reference allows a function to modify the original value of a variable. By referencing the sal variable directly, the function updates and prints the new salary without returning any value.

Program 3: Swapping Two Numbers with Before and After Output
Aim:
To swap two numbers using call by reference and display their values before and after swapping.

Apparatus / Software:
C++ Compiler

Text Editor or IDE

Algorithm:
Define a swap function that takes two integers by reference and exchanges their values using a temporary variable.

In main():

Declare two integers a and b.

Print their values before the swap.

Call the swap function.

Print their values after the swap.

Conclusion:
This program gives a clear demonstration of how reference passing works by showing the values before and after the function call. It reinforces the concept that reference variables allow direct modification of original data, which is useful in many real-world applications such as sorting, searching, and data processing.
