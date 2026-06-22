# 🤖 CodSoft Data Science Internship — Poras Nehra

[![Internship](https://img.shields.io/badge/Internship-CodSoft-blue?style=for-the-badge)](https://www.codsoft.in/)
[![Domain](https://img.shields.io/badge/Domain-Data%20Science-green?style=for-the-badge)](https://github.com/porasnehra/CODSOFT)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)](#)
[![Python](https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python)](https://www.python.org/)

---

## 👨‍💻 About Me

**Poras Nehra**
B.Tech Computer Science | Batch 2025–2029
Maharishi Markandeshwar Engineering College (MMEC), Mullana-Ambala

- 🔗 [LinkedIn](https://linkedin.com/in/poras-nehra-142170367)
- 🐙 [GitHub](https://github.com/porasnehra)

---

## 🏢 About CodSoft

CodSoft is a vibrant and diverse community that brings together individuals with a shared passion for technology, learning, and personal growth. Their internship programs provide real-world exposure to Data Science, Machine Learning, and AI through hands-on project work.

---

## 📋 Internship Details

| Field | Details |
|---|---|
| **Organization** | CodSoft |
| **Domain** | Data Science |
| **Mode** | Virtual / Remote |
| **Tasks Completed** | 3 / 3 (Minimum Required) |
| **Tools Used** | Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |

---

## ✅ Completed Tasks

### Task 1 — Titanic Survival Prediction
📁 [`titanic_dataset.ipynb`](./titanic_dataset.ipynb)

**Objective:** Build a model to predict whether a passenger on the Titanic survived or not.

**Approach:**
- Performed Exploratory Data Analysis (EDA) on the Titanic dataset
- Handled missing values (Age, Embarked, Cabin)
- Feature engineering: extracted title from name, created family size feature
- Applied Label Encoding for categorical variables
- Trained and evaluated models: Logistic Regression, Random Forest, Decision Tree
- Evaluated using Accuracy, Confusion Matrix, and Classification Report

**Key Insights:**
- Female passengers had a significantly higher survival rate
- Passengers in 1st class had the best survival chances
- Age and fare were important predictors

---

### Task 2 — Iris Flower Classification
📁 [`Iris_flower.ipynb`](./Iris_flower.ipynb)

**Objective:** Classify Iris flowers into three species — Setosa, Versicolor, and Virginica — based on sepal and petal measurements.

**Approach:**
- Loaded and explored the classic Iris dataset
- Performed visualizations: pair plots, heatmaps, violin plots
- Trained and compared multiple classifiers: KNN, SVM, Decision Tree, Random Forest
- Evaluated model performance using accuracy score and confusion matrix

**Key Insights:**
- Iris Setosa is linearly separable from the other two species
- Petal length and petal width are the most discriminative features
- Achieved near-perfect accuracy with SVM and KNN

---

### Task 3 — Credit Card Fraud Detection
📁 [`fraud_detection.ipynb`](./fraud_detection.ipynb)

**Objective:** Build a classification model to detect fraudulent credit card transactions from a highly imbalanced dataset.

**Approach:**
- Analyzed the highly imbalanced transaction dataset (fraud << legitimate)
- Applied SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance
- Feature scaling using StandardScaler
- Trained Random Forest and Logistic Regression classifiers
- Evaluated using Precision, Recall, F1-Score, ROC-AUC curve

**Key Insights:**
- Class imbalance is a critical challenge in fraud detection
- SMOTE significantly improved recall for the minority (fraud) class
- Random Forest outperformed Logistic Regression in F1-Score

---

## 🛠️ Tech Stack

```
Language     : Python 3.x
Libraries    : Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Imbalanced-learn
Environment  : Jupyter Notebook
Version Ctrl : Git & GitHub
```

---

## 📂 Repository Structure

```
CODSOFT/
├── titanic_dataset.ipynb       # Task 1: Titanic Survival Prediction
├── Iris_flower.ipynb           # Task 2: Iris Flower Classification
├── fraud_detection.ipynb       # Task 3: Credit Card Fraud Detection
└── README.md                   # This file
```

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/porasnehra/CODSOFT.git
cd CODSOFT
```

2. Install required libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open any `.ipynb` file and run all cells.

---

## 🙏 Acknowledgements

A huge thank you to **CodSoft** for providing this incredible opportunity to apply Data Science concepts to real-world datasets. This internship has strengthened my understanding of the complete ML pipeline — from data preprocessing and EDA to model building, evaluation, and interpretation.

---

> ⭐ If you find this repository helpful, please consider starring it!
