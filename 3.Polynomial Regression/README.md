<div align="center">

# 📉 Polynomial Regression

### Beginner-Friendly Implementation of Polynomial Regression using Python

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn Polynomial Regression Through Practical Datasets

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of **Polynomial Regression**, used when data follows a **non-linear relationship** that cannot be modeled accurately using a straight line.

These notebooks demonstrate:

- Non-linear data modeling  
- Polynomial feature transformation  
- Model training  
- Curve fitting  
- Prediction  
- Visualization of polynomial curves  

---

# 🧠 What is Polynomial Regression?

Polynomial Regression extends Linear Regression by adding **powers of input features** to model curved relationships.

### Formula:

\[
Y = b_0 + b_1X + b_2X^2 + b_3X^3 + ... + b_nX^n
\]

Where:

- **Y** = Predicted output  
- **X** = Input feature  
- **b₀** = Intercept  
- **b₁,b₂,b₃...** = Coefficients  
- **n** = Polynomial degree  

---

# 📂 Project Structure

## 1️⃣ Ice Cream Sales Prediction

📄 **Files**

- `icecream_polynomial.ipynb`
- `ice_cream_selling_data.csv`

### Objective:
Predict ice cream sales using temperature data.

### Concepts Covered:

✔ Polynomial Curve Fitting  
✔ Non-Linear Trend Modeling  
✔ Degree Selection  
✔ Sales Prediction  

---

## 2️⃣ Pressure vs Temperature Modeling

📄 **Files**

- `pressuretemp_PR.ipynb`
- `data.csv`

### Objective:
Model non-linear relationship between pressure and temperature.

### Concepts Covered:

✔ Polynomial Feature Transformation  
✔ Scientific Data Modeling  
✔ Curve Visualization  
✔ Higher Degree Regression  

---

## 3️⃣ Random Data Polynomial Regression

📄 **Files**

- `random_data_PR.ipynb`
- `randomdata_polynomial_regression.ipynb`

### Objective:
Practice polynomial regression on synthetic/random datasets.

### Concepts Covered:

✔ Model Behavior with Different Degrees  
✔ Overfitting vs Underfitting  
✔ General Polynomial Regression Practice  

---

# ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

# 🔍 Workflow

```python
Import Dataset
   ↓
Preprocess Data
   ↓
Generate Polynomial Features
   ↓
Train Polynomial Model
   ↓
Make Predictions
   ↓
Visualize Polynomial Curve
```

---

# 📊 Sample Code

```python
from sklearn.preprocessing import PolynomialFeatures
from sklearn.linear_model import LinearRegression

poly = PolynomialFeatures(degree=3)

X_poly = poly.fit_transform(X)

model = LinearRegression()

model.fit(X_poly, y)
```

---

# 📈 Why Use Polynomial Regression?

Use Polynomial Regression when:

✅ Data is non-linear  
✅ Straight line gives poor fit  
✅ Curved patterns exist  
✅ Higher-order relationships exist  

---

# ⚠ Common Problem: Overfitting

Higher degree polynomials may:

- Fit training data too closely  
- Capture noise instead of patterns  
- Perform poorly on unseen data  

This project helps understand:

- Underfitting  
- Good fit  
- Overfitting  

---

# 📊 Evaluation Metrics

This project uses:

### Mean Squared Error (MSE)

MSE = (1/n) * Σ(y - ŷ)²

---

### R² Score

- Closer to **1** → Better fit  
- Lower value → Poor fit  

---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/kjuhi-18/Supervised-Machine-Learning.git
```

Go to directory:

```bash
cd Supervised-Machine-Learning/3.Polynomial\ Regression
```

Launch Jupyter:

```bash
jupyter notebook
```

Run notebooks individually.

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- How Polynomial Regression works  
- Difference between Linear vs Polynomial Regression  
- How polynomial features are generated  
- How curve fitting works  
- How model complexity affects performance  

---

# 📚 Topics Covered

- Polynomial Regression  
- Polynomial Features  
- Curve Fitting  
- Degree Selection  
- Overfitting  
- Underfitting  
- Non-Linear Prediction  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
