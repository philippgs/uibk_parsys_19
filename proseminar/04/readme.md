# Assignment 4, due November 6th 2019

The goal of this assignment is to extend the 3D heat stencil application of Assignment 3 to include multiple domain decomposition schemes and investigate the effect of non-blocking communication.

## Exercise 1

### Tasks

- Provide implementations for the 3D heat stencil application that rely on the three domain decomposition variants presented in the lecture.
- Measure their speedup and efficiency for multiple problem and machine sizes as in the previous exercise.
- Illustrate the data in appropriate figures and discuss them. What can you observe?

## Exercise 2

### Tasks

- Switch from blocking communication to non-blocking communication (or vice versa) and measure the application again.
- Illustrate the data in appropriate figures and discuss them. Can you observe any difference?

## General Notes

All the material required by the tasks above (e.g. code, figures, etc...) must be part of the solution that is handed in. Your experiments should be reproducible and comparable to your own measurements using the solution materials that you hand in. For source code, please provide a makefile or other, intuitive means of compiling with the required flags and settings.

**Every** member of your group must be able to explain the given problem, your solution, and possible findings. You may also need to answer detailed questions about any of these aspects.

**Please run any benchmarks or heavy CPU loads only on the compute nodes, not on the login node.**
If you want to do some interactive experimentation, use an *interactive job* as outlined in the tutorial. Make sure to stop any interactive jobs once you are done.
