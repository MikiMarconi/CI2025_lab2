# TSP Laboratory – Genetic Algorithms

## Problem Description
The **Travelling Salesman Problem (TSP)** is a classic combinatorial optimization problem where, given a set of cities and the distances between them, the goal is to find the shortest possible route that visits each city exactly once and returns to the starting point.

## Genetic Operators
Two mutation operators and two crossover operators were implemented and compared during the experiments.

### Mutation Operators
- **Swap Mutation**: randomly selects two cities in the tour and swaps their positions.  
- **Insert Mutation**: removes a city and reinserts it at a different position in the tour.

### Crossover Operators
- **OX (Order Crossover)**: copies a subsequence from one parent and fills the remaining positions according to the order in the second parent, preserving the relative ordering of cities.  
- **PMX (Partially Mapped Crossover)**: exchanges corresponding segments between parents and applies a mapping to maintain valid city positions without duplicates.

## Conclusions
To better visualize and compare the effects of different operators and configurations, several **performance plots** were generated.   
The visual comparisons highlight how each combination of crossover and mutation affects the overall performance of the genetic algorithm.