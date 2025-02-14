# Gradient Descent from First Principles

An implementation of the gradient descent algorithm built from scratch, demonstrating the fundamental calculus concepts that power modern machine learning optimization.

## Project Overview

This project provides a ground-up implementation of gradient descent from first principles—without relying on pre-built optimization libraries. It includes:

* Visual demonstrations of critical concepts using 3D plots and contour analysis
* Step-by-step derivation of gradient calculations
* Pure Python implementation of gradient descent
* Interactive visualizations of the optimization process
* Comprehensive mathematical explanations with practical examples

## Key Features

* Custom implementation of numerical partial derivatives
* Visualization of local linearity and its role in optimization
* Interactive 3D surface plots with gradient descent paths
* Detailed explanation of learning rates and their impact
* No dependencies on machine learning libraries for core algorithm

## Getting Setup to View Project

For a quick view, you can check out the [optimization.pdf](optimization.pdf) doc. However, the project includes 3D renderings that are best viewed by running the full Jupyter Notebook.

1. Clone down the repository

    `git clone https://github.com/charliebailey24/gradient-descent-implementation.git`

2. Navigate into the project directory

    `cd gradient-descent-implementation`

3. Create and activate a virtual environment

    `python -m venv .venv`

    `source venv/bin/activate`

4. Install dependencies

    `pip install -r requirements.txt`

5. Launch Jupyter and open the notebook

    `jupyter notebook optimization.ipynb`

## Future Improvements

* Extend implementation to include different optimization algorithms (Adam, RMSprop)
* Add additional test functions and visualization options