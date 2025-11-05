# Traveling Salesman Problem (GA)

This project solves symmetric TSP instances using a Genetic Algorithm. Datasets are NumPy distance matrices in lab2/problem_{g|r1|r2}_{10|20|50|100|200|500|1000}.npy.

Approach
- Representation: permutation of cities; fitness = tour length.
- Selection: tournament; full generational replacement with best tracking.
- Crossover: Order Crossover (OX) and Partially Mapped Crossover (PMX).
- Mutation: Swap and Insertion.
- Hyperparameters scaled with size to keep runtime reasonable.

Experiments
- Grid across categories (g, r1, r2), sizes (10–1000), and operator pairs {OX, PMX}×{Swap, Insert}.
- Collected best tour length and runtime per run.
- Plots in the notebook show best length vs size and runtime vs size for each operator pair.

Results (summary)
- Best tour length increases with instance size, as expected; categories differ in difficulty.
- Runtime grows with size; operator choice impacts time and quality differently.
- See the final notebook cells for your plots; the best-performing pair in your runs is highlighted there.
