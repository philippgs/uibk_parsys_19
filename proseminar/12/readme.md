# Assignment 12, due January 22nd 2020

The goal of this assignment is to implement two basic applications in the Chapel programming model.

## Exercise 1

### Description

The Chapel programming model has been briefly discussed in the lecture. It is a high-level domain-specific language (DSL) that offers both shared and distributed memory parallelism.

### Tasks

- Download and install Chapel using [this download link](https://chapel-lang.org/download.html) and [this quickstart guide](https://chapel-lang.org/docs/usingchapel/QUICKSTART.html).
- Implement a parallel version of the Monte Carlo PI computation in Chapel and benchmark it for 1, 2, 4, and 8 threads on LCC2.
- Implement a parallel version of matrix multiplication in Chapel and benchmark it for 1, 2, 4, and 8 threads on LCC2.
- Enter your results in [this table](https://docs.google.com/spreadsheets/d/1Xklv7YoOBet34Q82SfKXc7K_bv_6E43UlxSStN7RDuc/edit?usp=sharing).

## Exercise 2

### Tasks

- If you haven't already done so, extend your Chapel installation to support distributed memory parallelism using [this guide](https://chapel-lang.org/docs/usingchapel/multilocale.html#readme-multilocale). Examples of environment variables to be used on LCC2 when compiling Chapel are `CHPL_LAUNCHER=gasnetrun_mpi` and `CHPL_COMM_SUBSTRATE=mpi`. You can then re-compile your Chapel programs and launch them directly by running `./chapel_program -nl <number_of_locales>` using a job submission script.
- If you haven't already done so, extend your Chapel programs to support distributed memory parallelism.
- Benchmark your distributed memory version for 1, 2, and 4 nodes on LCC2 using 8 threads add your results in the result table linked in Exercise 1.

## General Notes

All the material required by the tasks above (e.g. code, figures, etc...) must be part of the solution that is handed in. Your experiments should be reproducible and comparable to your own measurements using the solution materials that you hand in. For source code, please provide a makefile or other, intuitive means of compiling with the required flags and settings.

**Every** member of your group must be able to explain the given problem, your solution, and possible findings. You may also need to answer detailed questions about any of these aspects.

**Please run any benchmarks or heavy CPU loads only on the compute nodes, not on the login node.**
If you want to do some interactive experimentation, use an *interactive job* as outlined in the tutorial. Make sure to stop any interactive jobs once you are done.
