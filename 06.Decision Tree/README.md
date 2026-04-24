<div align="center">

# 🌳 Decision Tree

### Beginner-Friendly Implementation of Decision Tree Classification using Python

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn Decision Trees Through Real-World Classification Problems

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of **Decision Tree Classification**, one of the most intuitive and powerful supervised learning algorithms.

These notebooks demonstrate:

- Tree-based decision making  
- Feature splitting  
- Classification modeling  
- Model evaluation  
- Real-world datasets  

---

# 🧠 What is a Decision Tree?

A Decision Tree is a flowchart-like structure where:

- Each **node** represents a feature  
- Each **branch** represents a decision  
- Each **leaf** represents an output  

The model splits data based on conditions to make predictions.

---

# 🌿 Types of Decision Tree Algorithms

## 1️⃣ ID3 (Iterative Dichotomiser 3)

Uses **Entropy** and **Information Gain**.

### Entropy

```text
Entropy = - Σ p log₂(p)
```

### Information Gain

```text
IG = Entropy(parent) - Entropy(children)
```

✔ Works mainly for classification  
✔ Prefers features with highest information gain  

---

## 2️⃣ CART (Classification and Regression Trees)

Uses **Gini Index**.

```text
Gini = 1 - Σ p²
```

✔ Used in Scikit-learn  
✔ Supports both classification and regression  
✔ Produces binary trees  

---

# ⚖️ ID3 vs CART

| Feature | ID3 | CART |
|--------|-----|------|
| Metric | Entropy | Gini Index |
| Tree Type | Multi-branch | Binary |
| Tasks | Classification | Classification + Regression |
| Used in sklearn | ❌ | ✅ |

---

# 📂 Project Structure

## 1️⃣ Breast Cancer Classification

📄 Files

- `BreastCancer.csv`
- `BreastCancer_dt.ipynb`

### Objective

Predict whether a tumor is malignant or benign.

### Concepts Covered

✔ Medical Classification  
✔ Feature Splitting  
✔ Decision Tree Modeling  

---

## 2️⃣ Iris Classification

📄 Files

- `Iris.csv`
- `iris_dt.ipynb`

### Objective

Classify iris flower species.

### Concepts Covered

✔ Multi-Class Classification  
✔ Decision Boundaries  
✔ Model Accuracy  

---

## 3️⃣ iPhone Purchase Prediction

📄 Files

- `iphone_purchase.csv`
- `iphone_dt.ipynb`

### Objective

Predict whether a user will purchase an iPhone.

### Concepts Covered

✔ Customer Behavior Prediction  
✔ Feature-Based Classification  

---

## 4️⃣ Online Shoppers Intention

📄 Files

- `online_shoppers_intention.csv`
- `shppers_dt.ipynb`

### Objective

Predict whether a customer will make a purchase.

### Concepts Covered

✔ Real-world Dataset  
✔ Decision Tree Classification  
✔ Behavioral Analysis  

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
Train Decision Tree Model
   ↓
Split Data Based on Features
   ↓
Make Predictions
   ↓
Evaluate Model
```

---

# 📊 Sample Code

```python
from sklearn.tree import DecisionTreeClassifier

model = DecisionTreeClassifier(criterion='gini')

model.fit(X_train, y_train)
```

---

# 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

# ⚠ Common Problems

## Overfitting

Decision Trees can grow very deep and memorize data.

### Solution

- Limit depth (`max_depth`)  
- Use pruning  
- Use minimum samples split  

---

# 🔥 Why Use Decision Trees?

✔ Easy to understand  
✔ No need for feature scaling  
✔ Handles both numerical & categorical data  
✔ Interpretable models  

---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/kjuhi-18/Supervised-Machine-Learning.git
```

Go to directory:

```bash
cd Supervised-Machine-Learning/6.Decision\ Tree
```

Launch Jupyter:

```bash
jupyter notebook
```

Run notebooks individually.

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- How Decision Trees work  
- Difference between ID3 and CART  
- How splitting decisions are made  
- How to prevent overfitting  
- Real-world applications of Decision Trees  

---

# 📚 Topics Covered

- Decision Tree Classification  
- Entropy  
- Information Gain  
- Gini Index  
- CART Algorithm  
- ID3 Algorithm  
- Overfitting  
- Tree Splitting  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
