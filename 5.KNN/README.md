<div align="center">

# 🤖 K-Nearest Neighbors (KNN)

### Beginner-Friendly Implementation of KNN Classification and KNN Regression using Python

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn KNN Through Practical Classification and Regression Projects

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of:

- **KNN Classification**  
- **KNN Regression**

K-Nearest Neighbors (KNN) is a supervised learning algorithm used for both:

- Classification problems  
- Regression problems  

These notebooks demonstrate:

- Distance-based learning  
- Neighbor selection  
- Classification prediction  
- Regression prediction  
- Choosing optimal K value  
- Model evaluation  

---

# 🧠 What is KNN?

KNN predicts based on the nearest neighboring data points.

---

## For Classification

A new point is assigned the class most common among its K nearest neighbors.

```text
Distance = √[(x₂-x₁)² + (y₂-y₁)²]
```

---

## For Regression

Prediction is made using the average of nearby target values.

```text
Prediction = Average of K nearest neighbors
```

---

# 📂 Project Structure

# 📁 KNN_CLASSIFIER

## 1️⃣ Diabetes Classification

📄 Files

- `diabetes.csv`
- `knn_diabtes.ipynb`

### Objective

Predict whether a patient has diabetes.

### Concepts Covered

✔ KNN Classification  
✔ Feature Scaling  
✔ Distance Calculation  
✔ Medical Classification  

---

# 📁 KNN_REGRESSOR

## 2️⃣ Car Price Prediction

📄 Files

- `CarPrice_Assignment.csv`
- `car_knn_regr.ipynb`

### Objective

Predict car prices using KNN Regression.

### Concepts Covered

✔ KNN Regression  
✔ Feature-Based Prediction  
✔ Distance-Based Regression  

---

## 3️⃣ Iris Classification

📄 Files

- `Iris.csv`
- `iris_knn.ipynb`

### Objective

Classify iris flower species.

### Concepts Covered

✔ Multi-Class Classification  
✔ Neighbor Selection  
✔ Accuracy Analysis  

---

## 4️⃣ California Dataset

📄 Files

- `knn_class_regres_california.ipynb`

### Concepts Covered

✔ Combined KNN Practice  
✔ Classification and Regression Applications  

---

## 5️⃣ Sales Prediction

📄 Files

- `sales.csv`
- `sales.ipynb`

### Objective

Use KNN to analyze and predict sales patterns.

### Concepts Covered

✔ KNN Modeling  
✔ Sales Prediction  
✔ Feature-Based Learning  
✔ Practical Regression Application  

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
Feature Scaling
   ↓
Choose K Value
   ↓
Train KNN Model
   ↓
Make Predictions
   ↓
Evaluate Model
```

---

# 📊 Sample Code

## KNN Classification

```python
from sklearn.neighbors import KNeighborsClassifier

model = KNeighborsClassifier(n_neighbors=5)

model.fit(X_train, y_train)
```

---

## KNN Regression

```python
from sklearn.neighbors import KNeighborsRegressor

model = KNeighborsRegressor(n_neighbors=5)

model.fit(X_train, y_train)
```

---

# 📈 Evaluation Metrics

## Classification Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

## Regression Metrics

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

# ⚠ Importance of Choosing K

Small K:

- High variance  
- Can overfit  

Large K:

- High bias  
- Can underfit  

Choosing optimal K is critical.

---

# 🔥 Why Feature Scaling Matters

KNN uses distance calculations.

Features with larger values can dominate distance.

Use scaling methods like:

- StandardScaler  
- MinMaxScaler  

---

# ▶️ How to Run

Clone repository:

```bash
git clone https://github.com/kjuhi-18/Supervised-Machine-Learning.git
```

Go to directory:

```bash
cd Supervised-Machine-Learning/5.KNN
```

Launch Jupyter:

```bash
jupyter notebook
```

Run notebooks individually.

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- How KNN Classification works  
- How KNN Regression works  
- How distance-based learning works  
- How to choose K  
- Why scaling matters  
- Real-world KNN applications  

---

# 📚 Topics Covered

- KNN Classification  
- KNN Regression  
- Euclidean Distance  
- Feature Scaling  
- Model Tuning  
- Accuracy Metrics  
- Distance-Based Learning  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
