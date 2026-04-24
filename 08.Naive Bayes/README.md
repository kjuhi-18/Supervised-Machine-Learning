<div align="center">

# 📊 Naive Bayes

### Beginner-Friendly Implementation of Naive Bayes Classification using Python

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikitlearn">
<img src="https://img.shields.io/badge/Jupyter-Notebook-red?style=for-the-badge&logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-green?style=for-the-badge">

---

### 🚀 Learn Naive Bayes Through Real-World Classification Problems

</div>

---

# 📌 Overview

This directory contains beginner-friendly implementations of **Naive Bayes**, a probabilistic machine learning algorithm used for classification.

These notebooks demonstrate:

- Probability-based classification  
- Bayes Theorem  
- Feature independence assumption  
- Different types of Naive Bayes  
- Real-world datasets  

---

# 🧠 What is Naive Bayes?

Naive Bayes is based on **Bayes Theorem** and assumes that features are **independent**.

---

## 📐 Bayes Theorem

```text
P(A|B) = (P(B|A) * P(A)) / P(B)
```

---

# 🔍 Types of Naive Bayes

## 1️⃣ Gaussian Naive Bayes (Continuous Data)

Used when features are continuous (e.g., height, weight, age).

✔ Assumes data follows a **normal (Gaussian) distribution**

### Formula:

```text
P(x|y) = (1 / √(2πσ²)) * e^(-(x-μ)² / (2σ²))
```

### Used In:

- Iris dataset  
- Medical data  
- Numerical datasets  

---

## 2️⃣ Multinomial Naive Bayes (Count Data)

Used for **discrete counts** like:

- Word frequency  
- Number of occurrences  

✔ Common in **text classification**

### Example:

- Spam detection  
- Document classification  

---

## 3️⃣ Bernoulli Naive Bayes (Binary Data)

Used when features are **binary (0 or 1)**.

✔ Works on presence/absence of features  

### Example:

- Word present or not  
- Yes/No features  

---

# 📂 Project Structure

## 1️⃣ Customer Churn Prediction

📄 Files

- `Customer-Churn-Records.csv`
- `CustomerChurnPrediction.ipynb`

### Concepts Covered

✔ Binary Classification  
✔ Probability-Based Learning  

---

## 2️⃣ Social Network Ads

📄 Files

- `Social_Network_Ads.csv`
- `social_network_nb.ipynb`

### Concepts Covered

✔ Classification  
✔ User Behavior Prediction  

---

## 3️⃣ Iris Classification

📄 Files

- `Iris.csv`
- `iris_nb.ipynb`

### Concepts Covered

✔ Gaussian Naive Bayes  
✔ Multi-Class Classification  

---

## 4️⃣ Titanic Survival Prediction

📄 Files

- `titanic.csv`
- `titanic_nb.ipynb`

### Concepts Covered

✔ Real-world Dataset  
✔ Binary Classification  

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
Choose NB Type (Gaussian / Multinomial / Bernoulli)
   ↓
Train Model
   ↓
Make Predictions
   ↓
Evaluate Model
```

---

# 📊 Sample Code

## Gaussian NB

```python
from sklearn.naive_bayes import GaussianNB
model = GaussianNB()
```

---

## Multinomial NB

```python
from sklearn.naive_bayes import MultinomialNB
model = MultinomialNB()
```

---

## Bernoulli NB

```python
from sklearn.naive_bayes import BernoulliNB
model = BernoulliNB()
```

---

# 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

---

# ⚠ Important Points

- Assumes feature independence  
- Works well with small datasets  
- Fast and efficient  
- Performs well in text classification  

---

# 🔥 Why Use Naive Bayes?

✔ Simple and fast  
✔ Works well for classification  
✔ Handles high-dimensional data  
✔ Requires less training data  

---

# 🎯 Learning Outcomes

By completing these notebooks, you will understand:

- Bayes Theorem  
- Difference between Gaussian, Multinomial, Bernoulli  
- When to use each type  
- Probability-based predictions  
- Real-world applications  

---



<div align="center">

## ⭐ If this helped you, consider giving the repository a star.

</div>
