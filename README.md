# Practice 1.1 — OpenMP (TSP)
OpenMP-based parallelization of a sequential greedy solution for the Travelling Salesman Problem (TSP). The work includes data-dependency analysis, a parallelization strategy, and an evaluation of runtime and speedup across different numbers of cores (results collected in an Excel sheet).

## Files
- `*.c` — source code
- `*.pdf` — report
- `*.xlsx` — results and plots

## Build & Run
```bash
gcc -O2 -fopenmp main.c -o main
./main
