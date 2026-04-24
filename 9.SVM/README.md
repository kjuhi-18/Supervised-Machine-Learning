<div align="center">

# ⚡ Support Vector Machine (SVM)

### Beginner-Friendly Implementation of SVM for Classification using Python

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn SVM Through Real-World Classification Problems

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of **Support Vector Machine (SVM)**, a powerful supervised learning algorithm used for classification.

These notebooks demonstrate:

- Linear and non-linear classification  
- Margin maximization  
- Kernel tricks  
- Real-world datasets  

---

# 🧠 What is SVM?

SVM finds the **best boundary (hyperplane)** that separates classes with the **maximum margin**.

---

## 🎯 Key Idea

- Choose a boundary that is farthest from nearest data points  
- These nearest points are called **Support Vectors**

---

# 📐 Hyperplane Equation

```text
w · x + b = 0
```

Where:

- **w** → weight vector  
- **x** → input features  
- **b** → bias  

---

# 📏 Margin

Distance between hyperplane and closest points.

✔ Larger margin → better generalization  

---

# ⚙️ Types of SVM

## 1️⃣ Linear SVM

Used when data is linearly separable.

✔ Straight decision boundary  

---

## 2️⃣ Non-Linear SVM

Used when data is not linearly separable.

✔ Uses **Kernel Trick**

---

# 🔑 Kernel Trick

Transforms data into higher dimensions.

## Common Kernels:

- Linear  
- Polynomial  
- RBF (Radial Basis Function)  
- Sigmoid  

---

# 📂 Project Structure

## 1️⃣ Customer Churn Prediction

📄 Files

- `Customer-Churn-Records.csv`
- `CustomerChurnPrediction.ipynb`

### Concepts Covered

✔ Binary Classification  
✔ Customer Behavior Prediction  

---

## 2️⃣ Social Network Ads

📄 Files

- `Social_Network_Ads.csv`
- `social_svm.ipynb`

### Concepts Covered

✔ Classification  
✔ Decision Boundary  

---

## 3️⃣ Cancer Classification

📄 Files

- `cancer.csv`
- `cancer_svm.ipynb`

### Concepts Covered

✔ Medical Dataset  
✔ High Accuracy Classification  

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
Train SVM Model
   ↓
Choose Kernel
   ↓
Make Predictions
   ↓
Evaluate Model
```

---

# 📊 Sample Code

```python
from sklearn.svm import SVC

model = SVC(kernel='rbf')

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

# 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

# ⚠ Important Points

- Requires feature scaling  
- Sensitive to choice of kernel  
- Works well in high-dimensional space  
- Can be slow on large datasets  

---

# 🔥 Why Use SVM?

✔ Effective in high dimensions  
✔ Works well with clear margin separation  
✔ Flexible with kernel functions  
✔ Robust against overfitting (with proper tuning)  

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- What SVM is  
- What support vectors are  
- Difference between linear and non-linear SVM  
- How kernels work  
- How to apply SVM to real-world problems  

---

# 📚 Topics Covered

- Support Vector Machine  
- Hyperplane  
- Margin  
- Kernel Trick  
- Linear SVM  
- Non-Linear SVM  
- Classification  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
