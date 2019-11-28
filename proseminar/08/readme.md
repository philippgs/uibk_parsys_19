# Assignment 8, due December 4th 2019

The goal of this assignment is to parallelize several applications with OpenMP.

## Exercise 1

### Tasks

- Use OpenMP to parallelize the Monte Carlo computation of π of Assignment 2 and the 2D heat stencil simulation of Assignment 3.
- Measure the execution time of your OpenMP programs for several problem sizes and for 1 to 8 threads.
- Illustrate the data in appropriate speedup/efficiency figures and discuss them. What can you observe?
- Try to maximize their performance by considering all sequential and parallelism-related optimizations we discussed so far. Which did you choose and why?

## Exercise 2

### Tasks

- Use OpenMP to develop a parallel matrix multiplication program.
- Measure the execution time of your OpenMP programs for several matrix sizes and for 1 to 8 threads.
- Illustrate the data in appropriate speedup/efficiency figures and discuss them. What can you observe?
- Try to maximize the performance by considering all sequential and parallelism-related optimizations we discussed so far. Which did you choose and why?

## General Notes

All the material required by the tasks above (e.g. code, figures, etc...) must be part of the solution that is handed in. Your experiments should be reproducible and comparable to your own measurements using the solution materials that you hand in. For source code, please provide a makefile or other, intuitive means of compiling with the required flags and settings.

**Every** member of your group must be able to explain the given problem, your solution, and possible findings. You may also need to answer detailed questions about any of these aspects.

**Please run any benchmarks or heavy CPU loads only on the compute nodes, not on the login node.**
If you want to do some interactive experimentation, use an *interactive job* as outlined in the tutorial. Make sure to stop any interactive jobs once you are done.
