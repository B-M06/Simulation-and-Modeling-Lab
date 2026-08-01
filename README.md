# SIM Lab 1 — NumPy Scalar, Array & Matrix Operations

A Jupyter notebook lab exploring core NumPy operations — from scalar/array math to matrix statistics and visualization — using `numpy`, `sympy`, `matplotlib`, and `seaborn`.

## Overview

This lab is organized into four tasks, each building on the previous:

1. **Scalar & Array Operations** — trigonometric, exponential, logarithmic, and rounding functions applied to a 1D array.
2. **Matrix Operations (3×2)** — the same set of element-wise functions applied to a 2D matrix.
3. **Vector Functions on a Matrix (2×3)** — max/min with indices, vector norm, sorting, sum, product, and descriptive statistics.
4. **Bonus: Visualization & Randomization** — replacing static inputs with `np.random.uniform()` and visualizing the result with a `seaborn` heatmap.

## Contents

| Task | Description |
| Task 1 | Scalar & array operations: `sin`, `cos`, `tan`, `arcsin`, `arccos`, `arctan`, `exp`, `log`, `abs`, `sqrt`, `remainder`, `round`, `floor`, `ceil` |
| Task 2 | Same operations applied to a 3×2 matrix |
| Task 3 | Vector functions on a 2×3 matrix: max/min (with index), vector length (norm), row-wise & full sort (descending), sum, product, median, mean, standard deviation |
| Bonus | Random matrix generation (`np.random.uniform`) + heatmap visualization (`seaborn.heatmap`) |

## Requirements
-numpy
-sympy
-matplotlib
-seaborn


## Usage

1. Clone this repository.
2. Open the notebook in Jupyter, JupyterLab, or Google Colab:

   jupyter notebook SIM_Lab1_Bristy_Mandal_1021.ipynb
  
3. Run all cells in order — each task's markdown header marks the start of that section.

## 📊 Key Concepts Demonstrated

- **Element-wise math functions** on arrays and matrices (trigonometric, exponential, logarithmic, rounding)
- **Index-aware reductions** using `np.argmax` / `np.argmin` with `np.unravel_index`
- **Vector norms** via `np.linalg.norm`
- **Sorting** along an axis (`np.sort(axis=1)`) versus sorting a flattened array (`.flatten()`)
- **Descriptive statistics**: sum, product, median, mean, standard deviation
- **Random data generation** with `np.random.uniform`
- **Data visualization** with `seaborn.heatmap`
