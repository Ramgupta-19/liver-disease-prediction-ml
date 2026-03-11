# Liver Disease Prediction using Machine Learning

## Overview

This project uses machine learning algorithms to predict liver disease based on medical test results. The model classifies patients into different categories such as:

* No Disease
* Hepatitis
* Fibrosis
* Cirrhosis

The project demonstrates the complete data science workflow including **data preprocessing, exploratory data analysis (EDA), model building, and evaluation**.

---

## Dataset

The dataset contains **615 patient records** and **13 medical attributes** including:

* Age
* Sex
* Albumin
* Bilirubin
* Cholesterol
* Creatinine
* Alkaline Phosphatase
* Alanine Aminotransferase
* Aspartate Aminotransferase
* Protein
* Gamma Glutamyl Transferase

---

## Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Outlier detection and treatment
* Label encoding for categorical variables

### 2. Exploratory Data Analysis

* Histograms
* Correlation heatmap
* Distribution analysis
* Category distribution

### 3. Machine Learning Models

The following models were implemented and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost
* K-Nearest Neighbors
* Support Vector Machine

---

## Model Performance

Best performing model:

Logistic Regression
Testing Accuracy: **~91.6%**

XGBoost achieved slightly higher accuracy but Logistic Regression was chosen for deployment due to its simplicity and interpretability.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## Project Structure

```
liver-disease-prediction-ml
│
├── Liver_Disease_Prediction.ipynb
├── dataset.csv
├── Liver Disease Prediction.pptx
├── requirements.txt
└── README.md
```

---

## Author

Ram Gupta
BCA Student | Data Science & AI Enthusiast
