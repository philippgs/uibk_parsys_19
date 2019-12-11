# Assignment 10, due January 8th 2020

The goal of this assignment is to write a hybrid MPI/OpenMP application.

## Exercise 1

### Tasks

- Implement a hybrid MPI/OpenMP parallel version of the 2D heat stencil.
- Use at least two specific performance optimizations (one for intra-node performance, one for inter-node performance) that were discussed in the lecture so far.
- Benchmark your problem for several problem sizes, numbers of threads and numbers of nodes. Include experiments with all nodes/cores. What can you observe?
- For at least one larger problem size / number of threads / number of nodes combination, benchmark and compare all four cases of a) no optimization b) MPI optimization only c) OpenMP optimization only d) both. What can you observe?

## General Notes

All the material required by the tasks above (e.g. code, figures, etc...) must be part of the solution that is handed in. Your experiments should be reproducible and comparable to your own measurements using the solution materials that you hand in. For source code, please provide a makefile or other, intuitive means of compiling with the required flags and settings.

**Every** member of your group must be able to explain the given problem, your solution, and possible findings. You may also need to answer detailed questions about any of these aspects.

**Please run any benchmarks or heavy CPU loads only on the compute nodes, not on the login node.**
If you want to do some interactive experimentation, use an *interactive job* as outlined in the tutorial. Make sure to stop any interactive jobs once you are done.
