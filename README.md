# matrix-average-comparison
This program takes positive integers as input into a 4x5 matrix, calculates the average of inner elements (non-border) and outer elements (border), and compares them. It validates input to ensure only positive values are entered and outputs whether the inner, outer, or both averages are equal.

README.md
Matrix Average Comparator

This program calculates and compares the averages of inner (non-border) and outer (border) elements of a 4x5 matrix.
Features

  Input Validation: Ensures only positive integers are entered into the matrix.
  Average Calculation: Computes the averages of border (outer) and non-border (inner) matrix elements.
  Comparison Output: Displays whether the inner average, outer average, or both are equal.

How to Use

  Compile the program using a C compiler (e.g., gcc):

gcc -o matrix_avg matrix_avg.c

Run the program:

  ./matrix_avg

  Follow the prompts to input positive integers for each matrix position.

Example

Sample Input:

Enter the element at position [0][0]: 1  
Enter the element at position [0][1]: 2  
...  

Sample Output:

The average of inner elements (4.50) is greater than the average of outer elements (3.25).

Requirements

  C compiler (e.g., GCC)

Purpose

This program demonstrates:

  Working with 2D arrays in C.
  Validating user input.
  Basic arithmetic operations and control structures.
