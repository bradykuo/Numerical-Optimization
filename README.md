# Numerical Optimization Algorithm Implementations

A comprehensive collection of classical optimization algorithms implemented in Python, including gradient descent, Newton's method, interior point methods (IPM), and specialized solvers for various optimization problems.

## Overview

This repository contains implementations of various optimization algorithms and solvers for different types of optimization problems. The implementations cover linear programming, quadratic programming, nonlinear optimization, and specialized problems like portfolio optimization and network flows.

## Project Structure

The project is organized into several categories:

### Gradient-Based Methods
- `gradient_descent_4var.py` - Gradient descent for 4-variable optimization
- `steepest_descent_method.py` - Implementation of steepest descent method
- `quadratic_opt_2d.py` - 2D quadratic optimization with visualization
- `quadratic_opt_3d.py` - 3D quadratic optimization

### Newton's Method
- `newton_2d.py` - Newton's method implementation in 2D
- `newton_3d.py` - Newton's method implementation in 3D

### Interior Point Methods (IPM)
- `interior_point_method_4d_lp.py` - 4D linear programming using IPM
- `interior_point_method_simple_lp.py` - Simple linear programming using IPM
- `max_flow_ipm_solver.py` - Network flow optimization using IPM
- `svm_ipm.py` - Support Vector Machine implementation using IPM

### Curve Fitting
- `curve_fitting_comparison.py` - Comparison of curve fitting methods
- `curve_fitting_gurobi.py` - Curve fitting using Gurobi optimizer
- `curve_fitting_least_squares.py` - Least squares implementation

### Specialized Optimization Problems
- `agricultural_pricing.py` - Agricultural pricing optimization
- `artificial_neural_network.py` - Neural network optimization
- `cg_method.py` - Conjugate gradient method
- `dea_ipm_.py` - Data Envelopment Analysis using IPM
- `ford_fulkerson_max_flow.py` - Ford-Fulkerson algorithm for max flow
- `kkt.py` - KKT conditions solver
- `pooling_problem.py` - Pool allocation optimization
- `portfolio.py` - Portfolio optimization
- `weber_problem_solver.py` - Weber problem using SOCP

## Dependencies

- NumPy
- Pandas
- Matplotlib
- Gurobipy (Gurobi Optimizer)
- SciPy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/optimization-algorithms.git
cd optimization-algorithms
```

2. Install required packages:
```bash
pip install numpy pandas matplotlib scipy gurobipy
```

3. Install Gurobi Optimizer (required for some implementations):
   - Visit [Gurobi's website](https://www.gurobi.com/) to obtain a license
   - Follow installation instructions for your platform

## Usage

Each implementation can be run independently. For example:

```python
# Running gradient descent
python gradient_descent_4var.py

# Running Newton's method
python newton_2d.py

# Solving portfolio optimization
python portfolio.py
```

## Features

- Various optimization algorithm implementations
- Visualization tools for 2D and 3D problems
- Support for different problem types:
  - Linear Programming
  - Quadratic Programming
  - Nonlinear Optimization
  - Network Flow
  - Portfolio Optimization
  - Support Vector Machines

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is available for academic and educational purposes.

## Acknowledgments

- Thanks to Gurobi for their optimization solver
- References to relevant academic papers and resources used in implementations
