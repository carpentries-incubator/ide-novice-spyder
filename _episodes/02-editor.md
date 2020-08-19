---
title: "Editor"
teaching: 5
exercises: 5
questions:
- "What are the expected features in an IDE editor?"
objectives:
- "Understand the purpose of the features of a code editor"
keypoints:
- "A code editor fundamentally reduces your cognitive load"
- "There is no need to use an IDE. It is just much harder work not to. (David Arno, Stackoverflow)"
---

Editor integrates tools for an easy to use, efficient editing experience. 

The Editor’s usual key features include:

* Syntax highlighting (`pygments`); 
* Real-time code and style analysis (`pyflakes` and `pycodestyle`);
* On-demand completion, calltips and go-to-definition features (`rope` and `jedi`);
* Function/Class browser, horizontal and vertical splitting.

## Expected Benefits

* Less time and effort
* Enforce coding standards
* Project management

## Let's Write our first version of Bingo Cards generator

Let use a dictionary whose keys will be the letters B, I, N, G and O. The values will be the lists of five numbers that appear under each letter. Remember the "Free" in the center space.

### Things to pay attention to:

* Static code analysis
* Syntax coloring
* Integrated help [CTRL+I] 
* Panel layout

> ## Batteries included
> `random` package of python's standard library has a `sample` function that returns k unique random elements from a population sequence or set.
{: .callout}


{% include links.md %}

