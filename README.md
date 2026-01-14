
# 1D Poisson Equation Solver using Finite Difference Method

## Overview
This repository contains a MATLAB implementation of a 1D Poisson equation solver using the
second-order central finite difference method. The numerical solution is validated against
an analytical solution and the order of accuracy is verified using RMS error analysis.

## Governing Equation
d²u/dx² = x⁴,   x ∈ (0,1)  
u(0) = u(1) = 0

## Exact Solution
u(x) = (x/30)(1 − x⁵)

## Numerical Method
- Second-order central finite difference
- Sparse tridiagonal matrix formulation
- Direct solver using MATLAB backslash operator

## Features
- Exact vs numerical comparison
- RMS error computation
- Order of accuracy estimation using log–log regression

## How to Run
1. Open MATLAB
3. Run:
   ```matlab
   main

