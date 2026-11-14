# Linear Regression From Scratch

A hands-on implementation of Linear Regression using Python and NumPy, without using Scikit-learn's built-in Linear Regression model.

## Project Overview

This project demonstrates how Linear Regression works internally by implementing Gradient Descent from scratch.

The model is trained on the Chicago Taxi dataset to predict taxi base fares based on trip distance.

## Repository Structure

```text
linear-regression-from-scratch/
│
├── data/
│   └── chicago_taxi_train.csv
│
├── notebooks/
│   └── Linear_Regression.ipynb
│
└── README.md
```

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- JupyterLab

## Implementation

The project covers:

- Data loading and preprocessing
- Feature scaling using Min-Max Normalization
- Linear Regression from scratch
- Mini-Batch Gradient Descent
- Weight and bias optimization
- Mean Squared Error (MSE) calculation
- Model evaluation using R² Score, MSE and MAE
- Regression line visualization

## Dataset

**Dataset:** Chicago Taxi Training Dataset

- Input Feature: `TRIP_MILES`
- Target Variable: `BASE FARE`

The dataset is stored in the `data/` directory.

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/linear-regression-from-scratch.git
```

Install dependencies:

```bash
pip install numpy pandas matplotlib jupyterlab
```

## Running the Project

Launch JupyterLab:

```bash
jupyter lab
```

Open the notebook inside the `notebooks/` directory and execute the cells sequentially.

## Learning Objectives

The main objective is to understand:

- How Linear Regression learns weight and bias.
- How Gradient Descent minimizes the loss function.
- How feature scaling affects model training.
- How to evaluate regression models.
- How to visualize predictions against actual observations.

---

**Project developed as part of my Machine Learning learning journey.**