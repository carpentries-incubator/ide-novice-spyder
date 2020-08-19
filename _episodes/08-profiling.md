---
title: "Profiling"
teaching: 5
exercises: 5
questions:
- "What is the point of profiling our code and how do we do it?"
objectives:
- "Understand the need for profiling"
- "To know the basic commands for profiling"
- "To know how to interpret the profiling results"
keypoints:
- "Skills of applying good practices in our code and improving performance require specific training and experience."
---

## Profiling

In Spyder the Profiler tab recursively determines the run time and number of calls for every function called in a file, breaking down each procedure into its smallest individual units.

This allows you to easily identify code bottlenecks, and points you toward the exact statements most critical for optimization, and measures the performance differences after changes.

## Let's profile our current code

At this time we must have a code with two files, one where a Bingo card is generated and printed, and another where we verify if it is a winning card, we will verify how long it takes to execute each operation.

### Things to pay attention to:

You can run Spyder’s Profiler by simply clicking within it in the Editor, or you can manually enter the name/path in the Profiler’s path box (top left of the tab). Either way, you can then run it on the file by clicking `Run ‣ Profile`, clicking Profile in the Profiler tab, or by pressing the configurable key (F10 by default).

Note that sometimes the times are too small to notice any difference, so it is necessary to run the same procedures many times. That's why in Jupyter Lab you have `%time` and `%timeit` magic commands.

{% include links.md %}

