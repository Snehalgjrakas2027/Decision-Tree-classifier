# 🛳 Titanic Survival Prediction using Decision Tree

This project implements a **Decision Tree Classifier** to predict passenger survival on the Titanic. It demonstrates real-world applications of supervised machine learning with proper data preprocessing and model evaluation.

---

## 🚀 Objectives

- Explore the Titanic dataset
- Apply **data preprocessing** (handling missing values, encoding categorical data, scaling)
- Build and train a **Decision Tree Classifier**
- Evaluate model accuracy and fine-tune hyperparameters

---

## 🧰 Steps

### 1. Data Preprocessing:
- **Missing values**: Imputed `Age` with median; dropped `Cabin`.
- **Categorical encoding**: Encoded `Sex` and `Embarked` with One-Hot Encoding.
- **Feature selection**: Removed irrelevant columns (`PassengerId`, `Ticket`, `Name`).

### 2. Model Training:
- Used `sklearn.tree.DecisionTreeClassifier`
- Hyperparameters tuned: `max_depth`, `min_samples_split`, `min_samples_leaf`

### 3. Model Evaluation:
- Calculated **Accuracy** and **Confusion Matrix**
- Plotted **Decision Tree Graph** (Optional: using Graphviz)

---



