# Practice 1.1 — OpenMP (TSP)

OpenMP-based parallelization of a sequential greedy solution for the Travelling Salesman Problem (TSP). Includes dependency analysis and performance evaluation (runtime/speedup).

## Files
- `*.c` — source code
- `*.pdf` — report
- `*.xlsx` — results and plots

## Build & Run
```bash
gcc -O2 -fopenmp main.c -o main
./main
