# Genetic_algo_optimization
Combinatorial optimization of coffee production systems with genetic algorithms

# Problem
Coffee is a perennial crop with annual production cycles. Each cycle consists of a series of agricultural activities that can be performed in different ways. The individual tasks and their combination have varied impacts on production and costs, subject to uncertainty from environmental variables like weather and pests. Optimizing the productive system can be defined as the combination of tasks that maximize profitability over a relevant number of periods.

# Variables
4 categories
24 variables
10 consecutive periods

# Relations
Production & Costs  
Crossed limits  
Base productivity adjustment  
Stochastic component  

# Complexity
1.05e+27 possible solutions
3.83e+21 feasible solutions

# Results
* Convergence to optimal scenarios (~600 generations), reaching on average >90% of the theoretical maximum value.
* Loss of genetic variability (~500 generations). Execution time is sensitive to the number of variables.
* Low probability of randomly creating viable combinations (1.38e-11). The initial population must meet constraints to ensure convergence.

