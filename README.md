# Numerical Methods

A personal project implementing and visualizing classic numerical methods from scratch in Python, using JupyterLab.

Built during the summer break after my first year of a Mathematics and Computer Science degree (L1 Math-Info).

---

## Content

### 01 — Root Finding
Implementation and comparison of two root-finding methods :

- **Bisection** — slow but guaranteed to converge
- **Newton-Raphson** — fast quadratic convergence, requires the derivative

### 02 — Interpolation
Reconstructing a function from a set of points :

- **Lagrange Interpolation** — single polynomial through all points
- **Cubic Splines** — piecewise polynomials, smooth and stable

### 03 — ODEs 
Numerical solving of Ordinary Differential Equations :
- Euler method
- Runge-Kutta 4
- Lotka-Volterra model (predator-prey)

---

## Stack

- Python 3
- NumPy
- Matplotlib
- SciPy
- JupyterLab

---

## How to run

```bash
conda activate base
jupyter lab
```

Then open any `.ipynb` notebook.
