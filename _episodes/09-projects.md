---
title: "Projects"
teaching: 10
exercises: 10
questions:
- "What is the purpose of using projects in an IDE?"
- "How to create and use a project in an IDE?"
objectives:
- "Understand the usefulness of using projects in an IDE"
- "Know the basic tools that allow you to create and use projects in Spyder."
keypoints:
- "There are standards and good practices for organizing the files of our programs. And they are worth keeping in mind, especially if we work in collaboration with others."
---

## Projects

In a IDE, a project is a way of indicating that your work is organized within a directory, under which there is supposed to be a known file structure.

Spyder allows users to associate a given directory with a Project, which offers several main advantages:

* Opening, closing or switching to a Project automatically saves and restores your editor layout and open files to exactly how you left off. This allows you to easily switch between many different development tasks without having to manually re-create your session for each one.

* Your project’s root directory is automatically added to the `PYTHONPATH`, so you can easily import and work with any modules and packages you create with zero setup.

* The project path is also used to automatically set your working directory, and can be used as an automatic preset for several modules, such as the *Find in Files* search location.

* You can browse all your Project files from the Project Explorer, regardless of your current working directory or File Explorer location.

* Projects are integrated with the git version control system, allowing you to commit files and open them or your repository in the gitk GUI right from within Spyder.


## Play Bingo

Finally you will write a program that simulates a game of Bingo for a single card. Begin by generating a list of all of the valid Bingo calls (B1 through O75). Once the list has been created you can randomize the order of its elements by calling the `shuffle` function in the `random` module. Then your program should consume calls out of the list and cross out numbers on the card until the card contains a winning line. Simulate 1,000 games and report the minimum, maximum and average number of calls that must be made before the card wins. You may find it helpful to import your previous code when completing this exercise.

## Let's create and organize our project

How would you organize the files on this project?. Let's think about the way we usually find them in public repositories. It's basically a matter of both ourselves and our colleagues finding things where we expect them to be.

Let's run the static analyzer and profiler again.


{% include links.md %}

