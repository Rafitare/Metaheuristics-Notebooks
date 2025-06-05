# 🧠 Metaheuristics Playground

This repository contains implementations of various **metaheuristic algorithms** applied to classic optimization problems like the **Knapsack Problem**, **Mathematical Functions optimization**, and the **Travelling Salesman Problem (TSP)**.

## 📁 Contents

| Algorithm                  | Problem Type       | Notebook/Script                        |
|---------------------------|--------------------|----------------------------------------|
| Random Search             | Knapsack           | `1_random_search.py`                   |
| Hill Climbing             | Knapsack           | `2_hill_climbing.py`                   |
| Tabu Search               | Knapsack + TSP     | `3_tabu_search.py`                     |
| Simulated Annealing       | TSP + Knapsack     | `4_simulated_annealing.py`            |
| Genetic Algorithm (binary)| Knapsack           | `5_genetic_algorithm.py`              |
| Genetic Algorithm (real)  | Mathematical Function    | `6_ga_continuous_optimization.py`     |
| Particle Swarm Optimization | Mathematical Function  | `7_particle_swarm_optimization.py`    |
| Ant Colony Optimization   | TSP                | `8_ant_colony.py`                      |
| Harmony Search Variants   | TSP                | `9_harmony_search_tsp.py`             |

## 🎯 Problems Covered

- **Knapsack Problem** – Select items with max value under a weight constraint.
- **Mathematical Function Optimization** – Minimize different functions.
- **Travelling Salesman Problem (TSP)** – Find the shortest tour through all cities.

## 🛠️ Algorithms Implemented

- Random Search
- Hill Climbing
- Tabu Search
- Simulated Annealing
- Genetic Algorithm (binary and real-valued)
- Particle Swarm Optimization (PSO)
- Ant Colony Optimization (ACO)
- Harmony Search (HS, IHS, EHS, EIHS)


## 📈 Visualisations

For several algorithms, convergence plots and performance visualizations were included to better understand their behavior over time. These visualizations help illustrate:

- How quickly each algorithm approaches an optimal or near-optimal solution
- The effect of different parameter settings (e.g. mutation rate, temperature, population size)
- Performance comparisons between algorithm variants (e.g. GA vs PSO, HS vs EIHS)

Matplotlib was used for generating plots of fitness values across generations or iterations.

## 🧾 Datasets

All datasets used are stored in the `data` directory and are organized as follows:

- `data/knapsack/`
  - `knapsack-20.txt` – Small instance with 20 items
  - `rucsac-200.txt` – Larger instance with 200 items

- `data/tsp/`
  - Contains all TSP instances used, such as `berlin52.tsp`, `kroE100.tsp`, `pr1002.tsp`, etc.
  - Formats follow the [TSPLIB](http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/) standard


## 📊 Features

- Tested on multiple problem instances and datasets
- Parameter tuning and comparisons
- Benchmark datasets
- Easy to run and adapt for new problems
