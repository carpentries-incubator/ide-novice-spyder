---
title: "Debugging"
teaching: 10
exercises: 15
questions:
- "Why do we need to debug our programs?"
- "What is the basic debugging procedure and what are the features that allow me to do it?"
objectives:
- "Understand the need to debug programs"
- "Know the basic Spyder tools that allow us to debug a program"
keypoints:
- "Debugging is one of the most important skills related to programming and allows us to understand better our code, even if it works"
---

The main use of a debugger is to run the target program under controlled conditions that permit the programmer to track its operations in progress and monitor changes in computer resources that may indicate malfunctioning code.

This is probably one of the most important features of an IDE, since we programmers usually spend more time looking for errors in our programs than writing new code.

Debugging in Spyder is supported through integration with the enhanced `ipdb` debugger in the IPython Console. This allows breakpoints and the execution flow to be viewed and controlled right from the Spyder GUI, as well as with all the familiar IPython console commands.

Is supported by two tools:

* `pdb`, the Python Debugger, an interactive debugger, part of the Python standard library. It allows you to jump into a shell at arbitrary breakpoints in your code, where you can inspect the code and runtime, walkthrough the code line by line, change the values of objects, and more.

* `ipdb`, the IPython-enabled Python Debugger, is a third party interactive debugger with all pdb’s functionality and adds IPython support for the interactive shell, like tab completion, color support, magic functions and much more. You use ipdb just as you use pdb but with an enhanced user experience.

## The debugging procedure

1. The debugging is started by activating the debugger. It can be made either through the *Debug File* toolbar button, the *Debug>Debug* menu option, the `[CTRL+F5]` key or console's `debugfile` function.

2. Then, you advance through the code, the basic operation being to advance line by line, using the `n` (next) command from *pdb* in the terminal, or the *Run current line* button in the toolbar, or the *Debug>Step* menu option, or the `[CTRL+F10]` key.

3. Sometimes, you know that one part of the code works well, so you want to quickly advance to another part of the code. To do this you set a breakpoint and then advance using the *advance to next breakpoint* functions in the toolbar, the debug menu, or the `[CTRL+F12]` key.

4. If at any time you want to restart the debugging, you end it by using the *stop debug* option on the toolbar, the corresponding menu option or the `[CTRL+SHIFT+F12]` key. And you start the operation again.

The easiest way to set a breakpoint is to click on the left bar of the debugger on the line where you want the execution to stop.

## Let's debug our code

Launch the debugger and execute the code line by line, try the different options on the toolbar, the menu options, key combinations or console commands.

Check the changes that your code makes using both the interactive terminal and the variables browser.

> ## *pdb* Basic Commands
>  * `n[ext]` : `n` simply continues program execution to the next line in the current method
>  * `s[tep]` : `s` steps to the very next line of executable code, whether it is inside a called method or just on the next line
> On a line where a method is being called, `n` will “step over” the method execution code while `s` will “step into” the method execution code allowing you to introspect the method code.
>  * `w[here]` : `w` prints a stack trace, with the most recent frame at the bottom. An arrow indicates the “current frame”, which determines the context of most commands.
>  * `b[reak] ([filename:]lineno|function)` : `b` adds breakpoints to the specified locations.
> Example usage:
>      - `b sample-filename.py:<line no>`
>      - `b <function>`
>      - `b <lineno>` (for the current file)
>
>  * `c[ontinue]` : `c` continues program execution until another breakpoint is hit or the program execution completes
>  * `a[rgs]` : `a` prints out all the arguments the current function received
>  * `r[eturn]` : `r` continues execution until the current function returns
{: .callout}

{% include links.md %}

