# Genetic Algorithm Optimization
Combinatorial optimization of coffee production systems with genetic algorithms

## Introduction

This project focuses on optimizing coffee production systems through the application of genetic algorithms. Coffee, a perennial crop with annual production cycles, involves various agricultural tasks, each impacting production and costs differently. This optimization aims to find the task combination that maximizes profitability over significant periods, accounting for uncertainties like weather and pests.

## Problem Statement

Optimizing the productive system of coffee production entails defining the task combinations that maximize profitability, considering the cycle's inherent uncertainties. The challenge lies in navigating through the myriad of possible solutions (1.05e+27) to find the feasible ones (3.83e+21) that maximize profitability efficiently.

## Variables and Complexity

- **Categories**: 4
- **Variables**: 24
- **Periods**: 10 consecutive
- **Complexity**: The problem boasts a complexity of 1.05e+27 possible solutions, with 3.83e+21 being feasible.

## Relations

The model considers various factors such as production & costs, crossed limits, base productivity adjustments, and a stochastic component reflecting environmental uncertainties.

## Results

The optimization demonstrates that:
- Convergence to optimal scenarios occurs around 600 generations.
- The model achieves over 90% of the theoretical maximum value.
- A notable loss of genetic variability after 500 generations, pointing towards convergence.
- Execution time is highly sensitive to the number of variables considered.

## Challenges and Summary

This study underscores the feasibility of using genetic algorithms to model and optimize multivariate systems with intertemporal dependencies efficiently. Despite challenges such as computational costs and the need for model accuracy reflection, the approach presents a promising avenue for simulating and optimizing coffee production systems to maximize profitability.

For more details and discussions, feel free to reach out or contribute to the project.

## Contact

[@daniel-alpizar](https://github.com/daniel-alpizar)

![Genetic Algorithm Optimization Results](https://github.com/daniel-alpizar/Genetic_algo_optimization/assets/67352643/bd846d05-2097-4c13-aa34-0f5bc1ef93cf)

Feel free to explore the repository for more information on the methodology, results, and challenges encountered during this optimization project.
