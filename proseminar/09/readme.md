# Assignment 9, due December 11th 2019

The goal of this assignment is to implement the n-queens problem using OpenMP.

## Exercise 1

### Description

N-queens is a popular branch-and-bound problem. The goal is to compute the number of possible ways to place N chess queens on a NxN chess board without them attacking each other. See https://en.wikipedia.org/wiki/Eight_queens_puzzle for further information.

### Tasks

- Implement a sequential version of the n-queens problem. Benchmark your program for several problem sizes. What can you observe?
- Parallelize your program using OpenMP. Which OpenMP constructs are suitable candidates and why?
- Benchmark your problem for several problem sizes and numbers of threads. What can you observe?
- What are potential optimizations for this application?

## General Notes

All the material required by the tasks above (e.g. code, figures, etc...) must be part of the solution that is handed in. Your experiments should be reproducible and comparable to your own measurements using the solution materials that you hand in. For source code, please provide a makefile or other, intuitive means of compiling with the required flags and settings.

**Every** member of your group must be able to explain the given problem, your solution, and possible findings. You may also need to answer detailed questions about any of these aspects.

**Please run any benchmarks or heavy CPU loads only on the compute nodes, not on the login node.**
If you want to do some interactive experimentation, use an *interactive job* as outlined in the tutorial. Make sure to stop any interactive jobs once you are done.
