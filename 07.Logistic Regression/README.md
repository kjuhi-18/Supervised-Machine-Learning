<div align="center">

# 📊 Logistic Regression

### Beginner-Friendly Implementation of Logistic Regression for Classification Problems

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn Logistic Regression Through Real-World Classification Problems

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of **Logistic Regression**, a fundamental algorithm used for **classification tasks**.

These notebooks demonstrate:

- Binary classification  
- Probability prediction  
- Decision boundaries  
- Model evaluation  
- Real-world datasets  

---

# 🧠 What is Logistic Regression?

Logistic Regression is used to predict **probabilities** and classify data into categories.

Instead of a straight line, it uses a **Sigmoid Function**.

---

## 📈 Sigmoid Function

```text
σ(z) = 1 / (1 + e^(-z))
```

Where:

```text
z = b₀ + b₁x₁ + b₂x₂ + ... + bₙxₙ
```

### Output Range:

- Between **0 and 1**  
- Used as probability  

---

# 🎯 How Classification Works

- If output ≥ 0.5 → Class 1  
- If output < 0.5 → Class 0  

---

# 📂 Project Structure

## 1️⃣ Customer Churn Prediction

📄 Files

- `Customer-Churn-Records.csv`
- `CustomerChurnPrediction.ipynb`

### Objective

Predict whether a customer will leave (churn).

### Concepts Covered

✔ Binary Classification  
✔ Customer Behavior Analysis  
✔ Probability Prediction  

---

## 2️⃣ Cancer Classification

📄 Files

- `cancer.csv`
- `caner_lb.ipynb`

### Objective

Predict whether cancer is malignant or benign.

### Concepts Covered

✔ Medical Classification  
✔ Logistic Regression Modeling  

---

## 3️⃣ Iris Classification

📄 Files

- `Iris.csv`
- `iris_lr.ipynb`

### Objective

Classify iris species.

### Concepts Covered

✔ Multi-Class Classification  
✔ Decision Boundaries  

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
Train Logistic Regression Model
   ↓
Predict Probabilities
   ↓
Apply Threshold
   ↓
Evaluate Model
```

---

# 📊 Sample Code

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

# 📈 Evaluation Metrics

## Confusion Matrix

```text
           Predicted
         | 0 | 1 |
Actual 0 | TN | FP |
Actual 1 | FN | TP |
```

---

## Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

# ⚠ Important Points

- Logistic Regression is **not for regression**, it is for classification  
- Works well for linearly separable data  
- Sensitive to outliers  
- Requires feature scaling (recommended)  

---

# 🔥 Why Use Logistic Regression?

✔ Simple and fast  
✔ Probabilistic output  
✔ Easy to interpret  
✔ Works well for binary classification  

---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/kjuhi-18/Supervised-Machine-Learning.git
```

Go to directory:

```bash
cd Supervised-Machine-Learning/7.Logistic\ Regression
```

Launch Jupyter:

```bash
jupyter notebook
```

Run notebooks individually.

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- How Logistic Regression works  
- How probabilities are used for classification  
- How decision boundaries are formed  
- How to evaluate classification models  
- Real-world applications of classification  

---

# 📚 Topics Covered

- Logistic Regression  
- Sigmoid Function  
- Binary Classification  
- Multi-Class Classification  
- Confusion Matrix  
- Precision & Recall  
- Decision Boundary  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
