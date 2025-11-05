# Traveling Salesman Problem (GA)

This lab solves symmetric TSP instances using a Genetic Algorithm.
Approach
- Representation: permutation of cities; fitness = tour length.
- Selection: tournament; full generational replacement with best tracking.
- Crossover: Order Crossover (OX) and Partially Mapped Crossover (PMX).
- Mutation: Swap and Insertion.

Experiments
- Grid across categories (g, r1, r2), sizes (10–1000), and operator pairs {OX, PMX}×{Swap, Insert}.
- Collected best tour length and runtime per run.

Results 
- Best tour length increases with instance size.
- Runtime grows with size; operator choice impacts time and quality differently.

