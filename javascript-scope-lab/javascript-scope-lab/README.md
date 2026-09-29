# Lab - Scope

## Overview

This lab will further help you understand how functions and blocks determine scope in JavaScript.

The Flatburger restaurant is beginning to create its menu of food and drinks to sell to its customers. You will need to use your knowledge of scope to access and change some of these variables.

## Tools and Resources

It is recommended that you use the Visual Studio Code (VSCode) IDE for this lab.

Useful considerations and terminology:

**Scope**: The concept of where something is available.

**Globally-scoped variable**: A variable that is globally accessible and can be accessed from anywhere in the JavaScript script.

**Function-scoped variable**: A variable that can only be accessed inside of a function.

**Block-scoped variable**: A variable that can only be accessed inside of a block.

Here are some other useful resources:

- MDN
  - [Scope](https://developer.mozilla.org/en-US/docs/Glossary/Scope)
  - [ReferenceError: “x” is not defined](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Not_defined)

## Instructions

In this lab, you will practice declaring variables in **global scope**, creating variables that are **function-scoped**, and creating variables that are **block-scoped**.

**Fork and clone** this lab into your local environment. Navigate into its
directory in the terminal, then run `code .` to open the files in Visual Studio
Code.

These are your tasks:

- `burgers`: Declare a variable in global scope called `burgers` using the `const` keyword and assign it the value of an array that has the following 2 elements: `'Hamburger'` and `'Cheeseburger'`.
- `featuredDrink`: Declare a variable in global scope called `featuredDrink` using the `let` keyword and assign it the value `'Strawberry Milkshake'`.
- `addBurger()`: Write a function named `addBurger` that when called, does the following in this exact order:
  - Creates a **function-scoped** variable named `newBurger` using the `const` keyword and assigns it the value `'Flatburger'`.
  - Uses the `.push()` array method to add `newBurger` to the `burgers` array.
- `if(true)`: Write an `if` statement whose condition is `true`, so that the code in its block will always execute. The code inside of the `if` statement’s block should do the following in this exact order:
  - Create a **block-scoped** variable named `anotherNewBurger` using the `const` keyword and assign it the value `'Maple Bacon Burger'`.
  - Use the `.push()` array method to add `anotherNewBurger` to the `burgers` array.
- `changeFeaturedDrink()`: Write a function named `changeFeaturedDrink` that when called, changes the value of the `featuredDrink` variable to `'The JavaShake'`.

## Submission and Grading Criteria

When you're done with this lab, remember to commit and push your changes up to GitHub, then
submit your work to Canvas using CodeGrade.
