# MultiThreaded Sudoku Solver

MultiThreaded Sudoku Solver which can solve a valid NxN Sudoku.

## Features

- **Parallelism with Multithreading:** The program takes advantage of parallelism by implementing multi-threading using pthreads in C.
- **Dynamic Thread Spawning:** The program spawns 'N' threads depending on the input whenever it encounters an empty cell.
- **Efficient Execution:** The code was optimized for speed and correctness, running in approximately '0' seconds.

## Installation

To compile and run the project, follow these steps:

Compile the code:
```bash
gcc -o sudoku_solver sudoku_solver.c -lpthread
```

## Usage

To run the program, use the following command:
```bash
./sudoku.out grid_size inputfile%
