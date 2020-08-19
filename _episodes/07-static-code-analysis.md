---
title: "Static Code Analysis"
teaching: 5
exercises: 5
questions:
- "What is the purpose of performing a static or linting analysis of my code?"
objectives:
- "To understand the need and usefulness of linting in programming."
keypoints:
- "The code is not only improved to run better on the computer but especially so that it can be understood by other people."
---

## Static Code Analysis

Static Code Analysis tab offer information about style issues, bad practices, potential bugs, and other quality problems in your code.

Is called "static" because this analysis is made without having to actually execute your programs.

Spyder’s static analyzer uses [Pylint](https://www.pylint.org/) as back-end, which can intelligently detect an enormous and customizable range of problems. Check it out another time.

## Let's code Checking for a Winning Card

A winning Bingo card contains a line of 5 numbers that have all been called. Players normally record the numbers that have been called by crossing them out or marking them with a Bingo dauber. In this exercise we will mark that a number has been called by replacing it with an X in the Bingo card dictionary.

Write a function that takes a dictionary representing a Bingo card as its only parameter. If the card contains a line of five zeros (vertical, horizontal or diagonal) then your function should return True, indicating that the card has won. Otherwise the function should return False.

Create a main program that demonstrates your function by creating several Bingo cards, displaying them, and indicating whether or not they contain a winning line. You should demonstrate your function with at least one card with a horizontal line, at least one card with a vertical line, at least one card with a diagonal line, and at least one card that has some numbers crossed out but does not contain a winning line.

You will probably want to import your previous code when completing this exercise.

### Things to pay attention to:

Once you have finished your code, check any warning of error message in the editor or perform an static code analysis selecting `Source ‣ Run` static code analysis from the menubar, clicking the *Analyze* button in the dialog, or pressing the configurable static analysis key (`[F8]` by default). Cancel analyzing a file with the *Stop* button, and if analysis fails, click the *Output* button to find out why.

Try to fix all warning or error messages.


{% include links.md %}

