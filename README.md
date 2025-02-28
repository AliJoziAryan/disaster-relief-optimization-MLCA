# Disaster Relief Goods Distribution and Transportation Optimization
This project addresses the optimization of disaster relief goods distribution and transportation using a mathematical model and metaheuristic algorithms. The goal of this work is to minimize the total delivery time of relief goods to disaster-stricken regions, considering multiple warehouses, diverse vehicles, and order batching.

Key Contributions:
Mathematical Model: A Mixed-Integer Linear Programming (MILP) model is formulated to optimize the distribution of relief goods. This model minimizes the total delivery time and assigns relief orders to the most suitable warehouses and vehicles.
Metaheuristic Algorithms:
Multiple League Championship Algorithm (MLCA): A metaheuristic inspired by league championships used to solve complex combinatorial optimization problems.
League-based MLCA (L-MLCA) and Playoff-based MLCA (P-MLCA): Two novel variants of the MLCA are introduced to improve the optimization process.
Experimental Validation: The proposed algorithms are tested on various scenarios and compared with commercial solvers. The results demonstrate that P-MLCA outperforms the other algorithms in terms of both solution quality and computational efficiency.
Problem Overview:
The Relief Goods Distribution Problem (RGDP) involves:

Assigning relief orders to warehouses based on the availability of goods.
Allocating vehicles to transport these orders to disaster-stricken regions.
Optimizing the routing and batching of orders to minimize the overall delivery time.
Algorithms:
MILP Model: Provides an exact solution but is computationally expensive for larger problem instances.
MLCA: A metaheuristic inspired by football league championships, used to iteratively improve solutions.
L-MLCA: A variant where the teams from different leagues compete in a single league.
P-MLCA: A variant with a playoff system that involves direct elimination rounds for more efficient solution search.
