---
title: "Introduction"
teaching: 10
exercises: 0
questions:
- "What is an integrated development editor and why should I use it?"
- "Why you learn to program by programming"
objectives:
- "Understanding the benefits of using an IDE"
- "Understand the benefits of learning to program using a hands-on approach"
keypoints:
- "Having the tools in one place helps you save time and get a better overview of your project"
- "Programming is a skill that is learned firsthand, and there is great value in seeing others make mistakes and fixing them."
---

# Some questions 

Edit on the course pad https://pad.carpentries.org/cchome-spyder

* Introductions

* What is your programming experience?

* Which IDEs have you used?

* Do you feel you have gotten all the benefit out of them?

* How have you been taught to program?

# Let's generate a Bingo Card

The most common Bingo cards are flat pieces of cardboard or disposable paper which contain 25 squares arranged in five vertical columns and five side to side rows. Each space in the grid contains a number, except the middle square, which is designated a "Free" space.

A typical Bingo game utilizes the numbers 1 through 75. The five columns of the card are labeled 'B', 'I', 'N', 'G', and 'O' from left to right. The center space is usually marked "Free" or "Free Space", and is considered automatically filled. The range of printed numbers that can appear on the card is normally restricted by column, with the 'B' column only containing numbers between 1 and 15 inclusive, the 'I' column containing only 16 through 30, 'N' containing 31 through 45, 'G' containing 46 through 60, and 'O' containing 61 through 75.

The number of all possible Bingo cards with these standard features is P(15,5) × P(15,5) × P(15,5) × P(15,5) × P(15,4) = 552,446,474,061,128,648,601,600,000 or approximately 5.52×1026. 

We start making a program that generate a random Bingo card.

Let use a dictionary whose keys will be the letters B, I, N, G and O. The values will be the lists of five numbers that appear under each letter.

After that, we will write a code that displays the generated Bingo card on the terminal.

{% include links.md %}

