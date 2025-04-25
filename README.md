# Optimal Control Methods: Enumeration, Dynamic Programming, and QP

This repository contains descriptive solutions and implementations for optimal control problems using three approaches:
- **Enumeration-Based Optimization**: Explores all possible control sequences from a discretized control grid to find the one that minimizes the cost function. Suitable for small problems but becomes computationally expensive as the grid size increases.

- **Numerical Dynamic Programming**: Uses the principle of optimality and backward recursion over discretized state and control grids. Efficient for low-dimensional systems, but sensitive to grid resolution and interpolation strategy.

- **Quadratic Programming (QP)**: Solves the discrete-time Linear Quadratic Regulator (LQR) problem exactly using matrix algebra. Fast and accurate for linear systems with quadratic cost, and naturally supports state and control constraints.

![image](https://github.com/user-attachments/assets/adc5491e-d14b-4fa6-87d1-a1e43d6e4cd0)

![image](https://github.com/user-attachments/assets/8f6ed83d-2c4a-4a0b-a9ee-356814a9c473)

The methods are applied to linear systems with quadratic cost, highlighting trade-offs in accuracy, efficiency, and constraint handling.
