# Gradient Descent Algorithm Visualizer

A Machine Learning project that demonstrates how **Gradient Descent** works internally by visualizing the optimization process used in Linear Regression and other Machine Learning algorithms.

This project builds strong mathematical intuition behind optimization techniques by showing how parameters update iteratively to minimize the cost function.

---

## Overview

Gradient Descent is one of the most important optimization algorithms in Machine Learning and Deep Learning. It is used to minimize loss functions by updating model parameters step-by-step in the direction of steepest descent.

This project:

* Implements Gradient Descent from scratch
* Visualizes parameter updates over iterations
* Demonstrates cost function minimization
* Explains learning rate behavior
* Shows convergence of regression parameters
* Builds intuition for optimization in ML models

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Machine Learning Concepts Covered

### 1. Gradient Descent

An iterative optimization algorithm used to minimize a cost/loss function.

Gradient Descent update rule:

```text
θnew = θold - α ∂J(θ)/∂θ
```

Where:

* `θ` → model parameters
* `α` → learning rate
* `J(θ)` → cost function

---

### 2. Cost Function Optimization

The project minimizes prediction error by repeatedly updating parameters.

Example Mean Squared Error:

```text
J(θ) = 1/2m Σ(yi - ŷi)²
```

---

### 3. Learning Rate

The notebook explores how different learning rates affect convergence:

* Small learning rate → slow convergence
* Large learning rate → overshooting/divergence

---

### 4. Linear Regression

Gradient Descent is applied to optimize regression parameters.

Regression equation:

```text
y = mx + b
```

---

## Project Workflow

### Step 1 — Load Dataset

* Import dataset using Pandas/NumPy
* Select input and target variables

---

### Step 2 — Initialize Parameters

Initial values of:

* Slope (`m`)
* Intercept (`b`)

are initialized randomly or with zeros.

---

### Step 3 — Compute Predictions

Predictions are generated using the regression equation.

---

### Step 4 — Calculate Cost Function

The project computes prediction error using Mean Squared Error (MSE).

---

### Step 5 — Compute Gradients

Partial derivatives are calculated with respect to model parameters.

---

### Step 6 — Update Parameters

Parameters are updated iteratively using Gradient Descent.

---

### Step 7 — Visualization

The notebook visualizes:

* Cost reduction over iterations
* Regression line movement
* Convergence behavior
* Learning rate impact

---

## Key Insights

The project demonstrates:

* How Machine Learning models “learn”
* Why optimization is necessary
* Relationship between gradients and loss minimization
* Importance of choosing the right learning rate
* Convergence behavior in optimization algorithms

---

## License

This project is open-source and available under the MIT License.
