# Least Squares Regression and Functional Models

This project explores the **least-squares method** for fitting mathematical models to experimental data.

The objective is to determine which functional model best represents a given dataset by minimizing the sum of squared errors between observed values and predicted values.

This work was completed during my Erasmus exchange at **Linnaeus University (Sweden)**.

---

## Project Overview

The least-squares method is a mathematical technique used to approximate solutions to overdetermined systems of equations.

Given a system:

Ax = b

where **A** is a matrix of observations and **x** is the vector of unknown parameters, the least-squares solution minimizes the squared error between predicted and observed values.

This approach is widely used in:

- data analysis
- regression modeling
- machine learning
- statistics
- scientific computing

---

## Models Tested

Several functional models are tested on the dataset:

- Constant model
- Linear model
- Quadratic model
- Cubic model

Each model is evaluated using the least-squares method to determine which function best fits the observed data.

---

## Mathematical Approach

Two complementary approaches are used.

### Algebraic approach

Using the **normal equations**

AᵀAx = Aᵀb

to compute the least-squares solution.

### Statistical approach

Using regression analysis to estimate the parameters:

y = a₀ + a₁x

where:

- a₀ is the intercept
- a₁ is the slope

---

## Python Implementation

A Python script is used to compute the regression line using NumPy and visualize the results.

Libraries used:

- NumPy
- Matplotlib

The program computes the regression coefficients and plots the fitted model together with the dataset.

---

## Link with Machine Learning

The least-squares method is a fundamental concept in **machine learning**, particularly in supervised learning algorithms such as **linear regression**.

Working on this project helped me understand how mathematical optimization methods can be used to estimate model parameters from data.

It also provided an early introduction to ideas that are widely used in modern machine learning, such as:

- regression models
- error minimization
- model fitting
- data-driven prediction

This project contributed to my growing interest in **data analysis and machine learning methods**.

---

## Skills Demonstrated

This project demonstrates knowledge in:

- linear algebra
- regression analysis
- numerical methods
- mathematical modeling
- scientific programming with Python

---

## Author

Sandrine Daniel

---

## Academic Context

Course: Linear Algebra / Mathematical Modeling  
University: Linnaeus University (Sweden)  
Program: Erasmus Exchange Semester
