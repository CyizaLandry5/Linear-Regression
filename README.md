# Linear Regression

## Assignment Information

- **Student Name:** Mpayimana Cyiza Landry
- **Assignment Title:** Linear Regression
- **School:** Stanford Universirty
- **Course:** Supervised Machine Learning: Regression and Classification

---

## Assignment Overview

In this practice Assignment, I implemented linear regression with one variable to predict restaurant profits based on city population. The assignment involved building a complete linear regression model from scratch, including cost function computation, gradient descent implementation, and model evaluation.

---

## What I Learned

### 1. **Linear Regression Fundamentals**
- Understood the problem of predicting continuous values (profits)
- Learned the linear regression model: `f_w,b(x) = wx + b`
- Understood the relationship between features (population) and target (profit)

### 2. **Cost Function**
- Implemented the mean squared error cost function
- Learned how to evaluate model performance
- Understood the formula: `J(w,b) = (1/2m) * Σ(f_w,b(x) - y)²`

### 3. **Gradient Descent**
- Implemented batch gradient descent for parameter optimization
- Learned the update rules for w and b
- Understood the role of learning rate (alpha)

### 4. **Model Training**
- Trained a linear regression model on real data
- Visualized the learning process
- Made predictions on new data

### 5. **Data Visualization**
- Created scatter plots to understand data patterns
- Visualized the fitted linear model
- Interpreted results and made business decisions

---

## What I Accomplished

### ✅ Implemented Core Functions

1. **`compute_cost(x, y, w, b)`**
   - Computed the cost function for linear regression
   - Iterated over training examples
   - Calculated mean squared error

2. **`compute_gradient(x, y, w, b)`**
   - Computed gradients for gradient descent
   - Calculated partial derivatives for w and b
   - Returned both gradients for simultaneous update

### ✅ Built Complete Model

- **Dataset**: 97 training examples
- **Features**: 1 (city population)
- **Target**: Profit (in $10,000)
- **Training**: 1500 iterations
- **Learning Rate**: 0.01

### ✅ Achieved Understanding

- Discovered the relationship between population and profit
- Learned to optimize parameters using gradient descent
- Visualized the linear fit and made predictions
- Understood the business application of linear regression

---
