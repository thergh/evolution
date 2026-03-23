# Evolution Algorithm (TSP)

**A high-performance C++ implementation of an evolutionary metaheuristic for approximating solutions to the Travelling Salesman Problem (TSP).**

[![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B)](https://isocpp.org/)
[![TSP](https://img.shields.io/badge/Algorithm-Evolutionary-orange)](https://en.wikipedia.org/wiki/Evolutionary_algorithm)

*   **Evolutionary Metaheuristic:** Employs a population-based approach to explore the solution space of the Travelling Salesman Problem.
*   **Inversion Mutation:** Utilizes inversion mutation to maintain genetic diversity and escape local optima.
*   **Optimized Path Length Calculation:** Uses efficient incremental updates for objective function evaluations.
*   **Configurable Convergence:** The algorithm is finetunable with population size, mutation probability, and stagnation limits.
*   **PMX Crossover:** Implements the *Partially Mapped Crossover* (PMX) operator for effective recombination of genetic material.
*   **TSPLIB Support:** Built-in parser for standard `.tsp` file formats, supporting coordinate-based problem instances.