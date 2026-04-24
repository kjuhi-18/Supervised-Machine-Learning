<div align="center">

# 📉 Ridge and Lasso Regression

### Beginner-Friendly Implementation of Regularization Techniques using Python

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn Ridge and Lasso Regression Through Practical Datasets

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of **Ridge Regression** and **Lasso Regression**, two powerful **regularization techniques** used to reduce overfitting and improve model generalization.

These notebooks demonstrate:

- Ridge Regression (L2 Regularization)  
- Lasso Regression (L1 Regularization)  
- LassoCV (Automatic alpha tuning)  
- Feature selection  
- Regularization effects  
- Model evaluation  

---

# 🧠 What is Regularization?

Regularization helps prevent **overfitting** by penalizing large model coefficients.

It improves:

✅ Generalization  
✅ Model stability  
✅ Feature selection  
✅ Performance on unseen data  

---

# 📘 Ridge Regression (L2)

Ridge adds a penalty term:

```text
Cost Function = RSS + λΣβ²
```

Where:

- **RSS** = Residual Sum of Squares  
- **λ (lambda)** = Regularization strength  
- **β** = Model coefficients  

### Ridge shrinks coefficients, but does not eliminate them.

---

# 📗 Lasso Regression (L1)

Lasso adds a penalty term:

```text
Cost Function = RSS + λΣ|β|
```

### Lasso can:

- Shrink coefficients  
- Remove unimportant features (set coefficients to zero)  

This makes it useful for **feature selection**.

---

# 📂 Project Structure

## 1️⃣ Advertising Dataset

📄 Files

- `Advertising.csv`

### Ridge Models

- `advertising_ridge.ipynb`

### Lasso Models

- `advertising_lasso.ipynb`
- `advertising_lassoCV.ipynb`

### Concepts Covered

✔ Regularization on Advertising Data  
✔ Alpha Tuning  
✔ LassoCV  
✔ Feature Coefficient Analysis  

---

## 2️⃣ Boston Housing Dataset

📄 Files

- `boston.csv`

### Ridge Models

- `boston_ridge.ipynb`

### Lasso Models

- `boston_lasso.ipynb`
- `boston_lassoCV.ipynb`

### Concepts Covered

✔ House Price Prediction  
✔ Overfitting Reduction  
✔ Ridge vs Lasso Comparison  

---

## 3️⃣ Ice Cream Dataset

📄 Files

- `ice_cream_selling_data.csv`
- `icecream_ridge.ipynb`

### Concepts Covered

✔ Regularized Regression on Sales Data  
✔ Model Stability Analysis  

---

## 4️⃣ Combined Practice Notebooks

- `california_combine.ipynb`
- `tips_combine.ipynb`

### Concepts Covered

✔ Combined Regularization Practice  
✔ Comparing Multiple Approaches  

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
Train Ridge/Lasso Model
   ↓
Tune Alpha Parameter
   ↓
Evaluate Model
   ↓
Compare Results
```

---

# 📊 Sample Code

## Ridge Regression

```python
from sklearn.linear_model import Ridge

model = Ridge(alpha=1.0)

model.fit(X_train, y_train)
```

---

## Lasso Regression

```python
from sklearn.linear_model import Lasso

model = Lasso(alpha=1.0)

model.fit(X_train, y_train)
```

---

# 📈 Evaluation Metrics

This project uses:

## Mean Squared Error (MSE)

```text
MSE = (1/n) Σ(y - ŷ)²
```

---

## R² Score

```text
R² = 1 - (SSres / SStot)
```

---

# ⚠ Why Use Regularization?

Use Ridge or Lasso when:

- Too many features exist  
- Overfitting occurs  
- Multicollinearity exists  
- Model coefficients become unstable  

---

# 🔥 Ridge vs Lasso

| Feature | Ridge | Lasso |
|---------|------|-------|
| Penalty | L2 | L1 |
| Shrinks Coefficients | Yes | Yes |
| Eliminates Features | No | Yes |
| Feature Selection | No | Yes |

---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/kjuhi-18/Supervised-Machine-Learning.git
```

Go to directory:

```bash
cd Supervised-Machine-Learning/4.Ridge\ and\ Lasso\ Regression
```

Launch Jupyter:

```bash
jupyter notebook
```

Run notebooks individually.

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- What regularization is  
- How Ridge works  
- How Lasso works  
- Difference between L1 and L2 penalties  
- How Lasso performs feature selection  
- How to reduce overfitting  

---

# 📚 Topics Covered

- Ridge Regression  
- Lasso Regression  
- LassoCV  
- Regularization  
- Alpha Tuning  
- Overfitting  
- Feature Selection  
- Multicollinearity  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
