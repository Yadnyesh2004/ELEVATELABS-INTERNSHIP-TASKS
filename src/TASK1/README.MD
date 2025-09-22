1. Introduction

I built a simple calculator in Java that runs on the console. It allows the user to perform addition, subtraction, multiplication, and division. The program keeps running in a loop until the user chooses to exit.

2. Methods

I created four separate methods: add, subtract, multiply, and divide.
Each method takes two numbers as input and returns the result.
For division, I also handled the error case if the second number is zero.

3. Main Program

In the main method, I used a Scanner to take input from the user.
First, I show a menu of operations (1 for Addition, 2 for Subtraction, etc.).
The user enters their choice, and then I ask them to input two numbers.

4. Switch Case

Based on the user’s choice, I use a switch statement to call the right method.
For example, if the user enters 1, it calls the add method.
The result is then displayed back to the user.

5. Looping

I used a while loop so that the calculator doesn’t stop after one calculation.
The program keeps showing the menu until the user enters 5, which means "Exit".

6. Example

For example, if the user chooses addition and enters 10 and 20, the program prints Result: 30.
If they try division with 0, it shows an error message instead of crashing.

7. Outcome

The outcome of this program is that I practiced using methods, loops, conditionals, and Java’s Scanner class.
It also shows how to design a menu-driven console program.

