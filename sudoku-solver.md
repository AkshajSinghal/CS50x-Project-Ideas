# Sudoku Solver

## Overview
Make a Sudoku Solver, which will solve every problem the user gives him. 
The object is to get one, and only one, of each digit in each row, column, and 3-by-3 block.

Technically speaking, it’s a “recursive backtracking” routine. It tries a number in a blank cell, then calls itself to try another number in another blank cell. If everything works out, we’re done. If we get stuck, it works backward, erasing the mistakes and trying again with a different starting number. It’s fun to watch; you just draw the puzzle on the screen right before each recursive call.

## Difficulty
Intermediate

## Core Features

 - Recursive Structure
 - State Detection
 - Sequential Guessing
 - Validation Logic
 - The "Backtrack" (Undo)
 - Visual Feedback

## Example Usage:
This is a Sudoku puzzle:
![Example-Problem](https://www.quora.com/Hey-Im-15-years-old-I-just-finished-cs50-and-now-I-need-ideas-for-CS50x-final-project-I-want-to-make-something-that-actually-solves-a-problem-or-something-unusual-using-my-web-programming-skills-that-I-gained)

This is what it looks like after the program solves it:
![Example-Usage](https://www.quora.com/Hey-Im-15-years-old-I-just-finished-cs50-and-now-I-need-ideas-for-CS50x-final-project-I-want-to-make-something-that-actually-solves-a-problem-or-something-unusual-using-my-web-programming-skills-that-I-gained)

## Concepts Used:

 - Recursive Backtracking
 - Constraint Satisfaction
 - Data Structures
 - Search and Iteration

## Possible Extensions:

 - Build a Sudoku Generator
 - Implement a Vision-Based Solver
 - Visualisation and Animation

> This idea was inspired by this [post](https://www.quora.com/Hey-Im-15-years-old-I-just-finished-cs50-and-now-I-need-ideas-for-CS50x-final-project-I-want-to-make-something-that-actually-solves-a-problem-or-something-unusual-using-my-web-programming-skills-that-I-gained) on Quora.
