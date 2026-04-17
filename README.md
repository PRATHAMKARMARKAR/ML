# Machine Learning Algorithms Implementation

## Overview

This repository contains implementations of fundamental Machine Learning algorithms using Python. The project currently includes Linear Regression, Multiple Linear Regression, and Gradient Descent. More algorithms will be added over time.

The goal of this project is to build a strong foundation in machine learning by implementing algorithms from scratch and understanding the underlying mathematics.

---

## Project Structure

```bash
ML/
│
├── data/
│   └── placement.csv
│
├── linear_regression/
│   └── simple_regression.ipynb
│
├── multiple_linear_regression/
│   └── multiple_lr.ipynb
│
├── gradient_descent/
│   ├── gradient_descent.ipynb
│   ├── gradient_descent_from_scratch.ipynb
│   └── animation.gif
│
└── README.md
```

---

## Implemented Algorithms

* Simple Linear Regression
* Multiple Linear Regression
* Gradient Descent

---

## Gradient Descent (Mathematical Understanding)

This project includes the implementation and understanding of Gradient Descent with proper mathematical formulation.

### 1. One-Dimensional Case

Loss Function (Mean Squared Error):

L(m) = (1/n) Σ (y - mx)²

Derivative with respect to m:

dL/dm = (-2/n) Σ x(y - mx)

Update Rule:

m = m - α * dL/dm

---

### 2. Multi-Dimensional Case

For multiple features:

y = w₁x₁ + w₂x₂ + ... + wₙxₙ + b

Loss Function:

L(w, b) = (1/n) Σ (y - ŷ)²

Partial Derivatives:

∂L/∂wⱼ = (-2/n) Σ xⱼ(y - ŷ)

∂L/∂b = (-2/n) Σ (y - ŷ)

Update Rules:

wⱼ = wⱼ - α * ∂L/∂wⱼ
b = b - α * ∂L/∂b

---

## Planned Additions

* Logistic Regression
* Polynomial Regression
* Regularization Techniques (Ridge, Lasso)
* Classification Algorithms
* Model Optimization Techniques

---

## Concepts Covered

* Supervised Learning
* Regression Techniques
* Gradient Descent Optimization
* Differentiation of Loss Functions
* Model Training and Prediction

---

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Dataset

* Dataset used: placement.csv
* Located in the `data/` directory
* Contains features related to student data for prediction tasks

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/PRATHAMKARMARKAR/ML.git
cd ML
```

2. Install dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebooks inside respective folders.

---

## Model Evaluation

The models are evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R squared score

---

## Future Scope

This repository will be continuously updated with more machine learning algorithms and improvements. The aim is to cover a wide range of ML concepts with practical implementations.

---

## Contributing

Contributions are welcome. You can fork the repository and submit pull requests.

---

## Author

Pratham Karmarkar
GitHub: https://github.com/PRATHAMKARMARKAR
