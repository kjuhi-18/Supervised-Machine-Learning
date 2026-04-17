<div align="center">

# 📊 Multiple Linear Regression

### Beginner-Friendly Implementation of Multiple Linear Regression using Python

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn Multiple Linear Regression Through Practical Datasets

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of **Multiple Linear Regression (MLR)**, an extension of Simple Linear Regression where **multiple independent variables** are used to predict a dependent variable.

These notebooks demonstrate:

- Data preprocessing  
- Feature selection  
- Handling multiple input variables  
- Model training  
- Prediction  
- Model evaluation  

---

# 🧠 What is Multiple Linear Regression?

Multiple Linear Regression predicts a target using **two or more independent variables.**

### Formula:

\[
Y = b_0 + b_1X_1 + b_2X_2 + ... + b_nX_n
\]

Where:

- **Y** = Predicted output  
- **b₀** = Intercept  
- **b₁,b₂...bn** = Feature coefficients  
- **X₁,X₂...Xn** = Independent variables  

---

# 📂 Project Structure

## 1️⃣ Advertising Sales Prediction

📄 **Files**

- `MLR_Advertising.ipynb`
- `Advertising.csv`

### Objective:
Predict sales using multiple advertising features:

- TV Budget  
- Radio Budget  
- Newspaper Budget  

### Concepts Covered:

✔ Multiple Feature Regression  
✔ Feature Contribution Analysis  
✔ Sales Prediction  
✔ Coefficient Interpretation  

---

## 2️⃣ Insurance Cost Prediction

📄 **Files**

- `MLR_Insurance.ipynb`
- `insurance.csv`

### Objective:
Predict insurance charges using:

- Age  
- BMI  
- Children  
- Smoking Status  
- Region  

### Concepts Covered:

✔ Categorical Variable Handling  
✔ Encoding  
✔ Multiple Regression Modeling  
✔ Insurance Cost Prediction  

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
Data Preprocessing
   ↓
Feature Selection
   ↓
Train MLR Model
   ↓
Make Predictions
   ↓
Evaluate Performance
```

---

# 📊 Sample Code

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

# 📈 Evaluation Metrics

This project uses common regression metrics:

### Mean Absolute Error (MAE)

\[
MAE = \frac{1}{n} \sum |y - \hat y|
\]

---

### Mean Squared Error (MSE)

\[
MSE = \frac{1}{n} \sum (y - \hat y)^2
\]

---

### R² Score

Measures model performance:

- Closer to **1** → Better model  
- Closer to **0** → Poor model  

---

# ⚠ Assumptions of Multiple Linear Regression

This project also introduces key MLR assumptions:

- Linearity  
- Independence  
- Homoscedasticity  
- No Multicollinearity  
- Normally Distributed Errors  

---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/kjuhi-18/Supervised-Machine-Learning.git
```

Go to directory:

```bash
cd Supervised-Machine-Learning/2.Multi\ Linear\ Regression
```

Launch Jupyter:

```bash
jupyter notebook
```

Run notebooks individually.

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- How Multiple Linear Regression works  
- How multiple features influence prediction  
- How coefficients are interpreted  
- How regression models are evaluated  
- Real-world applications of MLR  

---

# 📚 Topics Covered

- Multiple Linear Regression  
- Feature Selection  
- Coefficients  
- Model Training  
- Prediction  
- Encoding  
- Regression Metrics  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
