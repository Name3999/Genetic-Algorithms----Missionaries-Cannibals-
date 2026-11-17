# 🌊 Missionaries & Cannibals – Genetic Algorithm Solver

**Can evolution and artificial intelligence find the perfect way across the river?**

Missionaries & Cannibals is an interactive Artificial Intelligence project that explores one of the classic problems in AI: the River Crossing Puzzle, using a traditional Genetic Algorithm.

The challenge is simple to understand, but surprisingly difficult to solve: three missionaries and three cannibals must cross a river using a boat with limited capacity. However, the missionaries must never be outnumbered by cannibals on either riverbank, otherwise the rules of the puzzle are violated.

Our application approaches this problem through the principles of natural evolution, simulating how a population of candidate solutions evolves over successive generations to discover a valid and efficient crossing strategy.

### 🧬 Genetic Algorithm

The application implements the fundamental mechanisms of a classical Genetic Algorithm:

- **Population Initialization** – generates an initial population of candidate crossing sequences.
- **Fitness Evaluation** – evaluates each candidate based on its validity, efficiency, and ability to reach the goal.
- **Selection** – chooses better-performing individuals for reproduction.
- **Crossover** – combines genetic information from parent solutions to create new candidates.
- **Mutation** – introduces random changes to maintain diversity and explore new possibilities.
- **Evolution** – repeats the process across generations until a valid solution is discovered or a stopping condition is reached.

### 🚀 Key Features

- Interactive river-crossing simulation.
- Automatic puzzle solving using a Genetic Algorithm.
- Step-by-step visualization of the best solution.
- Visualization of population evolution across generations.
- Fitness score tracking and performance statistics.
- Configurable genetic parameters, such as population size, mutation rate, and crossover rate.
- Validation of crossing constraints and solution correctness.

### 🎯 Project Goals

Our main goal is to demonstrate how evolutionary computation can solve constraint-based problems through natural selection-inspired mechanisms.

By observing how candidate solutions evolve, users can understand how selection, crossover, mutation, and fitness evaluation work together to produce increasingly effective solutions.

---

**Developed as a university project for the Artificial Intelligence course.**

*Four developers. One population. Countless generations. One river to cross.*
