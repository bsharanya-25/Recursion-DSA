# Recursion Overview

## What is Recursion?
Recursion is a fundamental programming concept where a function calls itself to solve a problem. This process can occur either directly or indirectly, and the function involved is referred to as a recursive function.

## Types of Recursion
### Direct Recursion:
Direct recursion involves a function calling itself directly within its own code. This can be further categorized into four types:
- Tail recursion
- Head recursion
- Tree recursion
- Nested recursion

For detail explanation refer to: https://www.geeksforgeeks.org/types-of-recursions/

### Indirect Recursion:
Indirect recursion occurs when a function A calls another function B, which in turn eventually calls back function A, forming a cycle of function calls.

## Applications of Recursion
Recursion finds applications in various fields, including:
- **Search and Sorting Algorithms:** Recursive strategies are employed to search and sort intricate data structures like trees and graphs.
- **Mathematical Calculations:** Problems like factorials and the Fibonacci sequence are commonly solved using recursion.
- **Compiler Design:** Recursion is crucial in compiler design for parsing and analyzing programming languages.
- **Graphics:** Many graphical algorithms, such as fractal generation, utilize recursion to create intricate patterns.
- **Artificial Intelligence:** Recursive neural networks play a vital role in tasks like natural language processing and computer vision.

## Advantages of Recursion
- **Simplification:** Complex problems are broken down into smaller, more manageable components.
- **Readability:** Recursive code can often be more readable and intuitive compared to iterative solutions.
- **Essential for Certain Problems:** Some problems are inherently recursive in nature, making recursion the ideal approach.
- **Reduced Code Length:** Recursive solutions can often be more concise and easier to understand.

## Disadvantages of Recursion
- **Efficiency:** Recursive solutions can be less efficient in terms of memory and runtime compared to iterative solutions.
- **Debugging Complexity:** Debugging recursive code can be challenging, especially for deep recursion levels.
- **Stack Overflow:** If not managed properly, deep recursion can lead to stack overflow errors.

## Interview Topics

### Theoretical Questions
1. Understand the different types of recursion.
2. Differentiate between finite and infinite recursion with real-world examples.
3. Compare recursion and iteration in terms of their characteristics and use cases.
4. Explain the concept of implicit recursion and provide examples.
5. Define tail recursion and its advantages in optimization.
6. Discuss why tail recursion optimization is considered more efficient than regular recursion.

### DSA Questions
1. Calculate the factorial of a given number using recursion.
2. Generate the Fibonacci series using a recursive approach.
3. Implement a recursive power function to compute `x` raised to the power of `n`.
4. Write a recursive function to check if a given string is a palindrome.
5. Find the Greatest Common Divisor (GCD) of two positive integers using recursion.
6. Print numbers from 1 to `n` using recursion.
7. Compute the sum of elements in an array using recursion.
8. Perform binary search on a sorted array using recursion.
9. Implement the merge sort algorithm using recursion.
10. Reverse a given string using recursion.
11. Solve combination sum problems (I & II) using recursion.
12. Generate subsets of a set (I & II) using recursion.
13. Solve the N-Queens problem using a recursive approach.
14. Generate permutations of a sequence (I & II) using recursion.
15. Count paths in a grid using recursive techniques.
16. Solve the Tower of Hanoi problem using recursion.
17. Partition a string into palindromic substrings using recursion.
18. Generate balanced parentheses using recursion.
19. Evaluate arithmetic expressions using recursion.
20. Find connected components in a graph using recursive depth-first search (DFS).

You can refer to this GFG link below: https://www.geeksforgeeks.org/recursion-algorithms/?ref=lbp
