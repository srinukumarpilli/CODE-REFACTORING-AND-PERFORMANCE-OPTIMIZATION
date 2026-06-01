# CODE-REFACTORING-AND-PERFORMANCE-OPTIMIZATION

*COMPANY*: CODTECH IT SOLUTIONS PRIVATE LIMITED

*NAME*: PILLI SRINU KUMAR

*INTERN ID*: CITS69

*DOMAIN*: SOFTWARE DEVELOPMENT

*DURATIONS*: 4 WEEKS

*MENTOR*: NEELA SANTOSH KUMAR

##Introduction

Code refactoring is the process of improving the internal structure of existing code without changing its functionality. As software projects grow larger, the code can become difficult to understand and maintain. Refactoring helps developers write cleaner, more efficient, and reusable code.

In this task, an existing JavaScript project was selected and analyzed. The code was then modified to improve readability and performance while keeping the output unchanged.

Technologies Used
Visual Studio Code
JavaScript
HTML
Web Browser (Chrome/Edge)
Problem Statement

The original project contained code that was difficult to understand due to:

Poor variable naming
Repeated code blocks
Unnecessary comments
Complex logic
Lack of code organization

These issues made the project harder to maintain and slightly affected performance.

Project Description

A simple JavaScript application was chosen for refactoring. The application performs basic calculations and displays results on a webpage.

The goal was to improve the structure of the code while ensuring the application continued to work correctly.

Refactoring Techniques Applied
1. Improved Variable Names

Before Refactoring:

let a = 10;
let b = 20;
let c = a + b;

After Refactoring:

let firstNumber = 10;
let secondNumber = 20;
let totalSum = firstNumber + secondNumber;

Benefit:

Easier to understand.
Improves code readability.
2. Removed Duplicate Code

Before Refactoring:

console.log("Welcome");
console.log("Welcome");
console.log("Welcome");

After Refactoring:

for(let i = 0; i < 3; i++){
    console.log("Welcome");
}

Benefit:

Reduces code size.
Improves maintainability.
3. Created Functions

Before Refactoring:

let result1 = 10 + 20;
let result2 = 30 + 40;

After Refactoring:

function addNumbers(a, b){
    return a + b;
}

Benefit:

Reusable code.
Less repetition.
4. Removed Unused Variables

Before Refactoring:

let temp = 100;

After Refactoring:

Unused variable removed.

Benefit:

Reduces memory usage.
Cleaner code.
5. Simplified Logic

Before Refactoring:

if(status === true){
    return true;
}else{
    return false;
}

After Refactoring:

return status;

Benefit:

Cleaner and shorter code.
Faster execution.
Performance Optimization

Several optimization techniques were applied:

Reduced Unnecessary Loops

Removed loops that were not required and replaced them with efficient logic.

Reduced Memory Usage

Unused variables and temporary objects were removed.

Improved Function Reusability

Functions were created to avoid repeating the same code multiple times.

Cleaner Structure

Code was separated into smaller functions for better performance and maintenance.

Working Process
Step 1

Selected an existing JavaScript project.

Step 2

Reviewed the code and identified areas for improvement.

Step 3

Improved variable names and function names.

Step 4

Removed duplicate and unused code.

Step 5

Created reusable functions.

Step 6

Optimized loops and conditions.

Step 7

Tested the application to ensure the output remained unchanged.

Step 8

Compared the code before and after refactoring.

Changes Made
Area	Before	After
Variable Names	Short and unclear	Meaningful names
Duplicate Code	Present	Removed
Functions	Limited	Reusable functions
Logic	Complex	Simplified
Performance	Average	Improved
Readability	Difficult	Easy to understand
Results

After refactoring:

Code became easier to read.
Code became easier to maintain.
Duplicate code was removed.
Application performance improved.
Memory usage was reduced.
Function reusability increased.

The application produced the same output while using cleaner and optimized code.

Challenges Faced
Understanding existing code.
Identifying duplicate code.
Choosing meaningful variable names.
Ensuring output remained unchanged after refactoring.

These challenges were solved through testing and code analysis.

Learning Outcomes

Through this task, I learned:

Importance of clean coding practices.
Code refactoring techniques.
Performance optimization methods.
JavaScript best practices.
Function reusability.
Code organization and maintenance.

##OUTPUT

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/afe281de-382f-4a0d-a7f2-01289331ae7c" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/503d8cd1-6f1b-4986-a920-d0e7e66645e2" />
