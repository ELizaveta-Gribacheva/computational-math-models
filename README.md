# Systems and Models of Computational Mathematics

![Status](https://img.shields.io/badge/Status-Completed-success)
![Language](https://img.shields.io/badge/Language-Python-blue)
![Topic](https://img.shields.io/badge/Topic-Scientific%20Computing-purple)

This repository contains a comprehensive collection of mathematical models and simulations developed as part of the "Systems and Models of Computational Mathematics" course.

The project demonstrates the practical application of numerical methods for analyzing dynamic systems, stochastic processes, and real-world data processing.

## Implemented Projects

The project involves the development of software for modeling the following processes:

### 1. Deterministic Models (ODE Simulations)
Numerical methods (Runge-Kutta, `odeint` solver) were used to solve differential equations:
* **Epidemiology:** Implemented the **SIR** model to analyze infection spread and evaluate the effectiveness of quarantine measures.
* **Ecology:** Built the **"Predator-Prey"** (Lotka-Volterra) model with phase portraits of population stability.
* **Military Analytics:** Applied **Osipov-Lanchester** models to forecast conflict outcomes.

### 2. Stochasticity & Chaos
* **Chaos Theory:** Visualized strange attractors and analyzed sensitivity to initial conditions.
* **Cellular Automata:** Developed simulations to model complex systems using simple rules:
    * **Forest Fire Model:** Probabilistic model of forest fire spread.
    * **Game of Life:** Implementation of Conway's classic cellular automaton.

### 3. Data Fitting & Analysis
* Developed algorithms for model parameter fitting based on retrospective (historical) data.
* Conducted error analysis and model verification.

### 4. Optimization (Genetic Algorithms)
Implementation of evolutionary algorithms for finding global extrema of complex functions:
* **Booth Function:** Optimization using standard selection, crossover, and mutation.
* **Three-Hump Camel Function:** Advanced GA with **elitism** and **adaptive mutation** strategies.

## 🛠 Technologies

All models are implemented in **Python**.

* **NumPy & SciPy:** Core computations, solving systems of differential equations, optimization.
* **Matplotlib & Seaborn:** Visualization of results, plotting dependency graphs, time-based process animation.
* **Pandas:** Processing of input datasets.
* **IPython.display / Tkinter:** Creation of interactive interfaces and simulations.

## Visuals & Examples

### Game of Life Simulation
<img src="https://github.com/user-attachments/assets/df1a02b9-3c47-495c-ac76-0d7777a37b5e" width="600" alt="Game of Life Simulation" />

### Forest Fire Simulation
<img src="https://github.com/user-attachments/assets/1b5563c9-b4e2-4605-a71d-50b9079b0b6e" width="600" alt="Forest Fire Simulation" />

## Conclusions

Project Outcomes:
1. Created a toolkit for simulating real-world processes without the need for expensive physical experiments.
2. Automated the calculation process for complex non-linear systems.
