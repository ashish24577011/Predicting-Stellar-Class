# Stellar Classification using Machine Learning

## Overview

This project was developed for the Kaggle competition **"Predicting Stellar Class"**.

The objective is to classify astronomical objects into one of three categories:

* STAR
* GALAXY
* QSO (Quasi-Stellar Object)

The solution uses machine learning techniques including preprocessing, feature engineering, cross-validation, and model tuning to achieve high classification performance.

---

## Dataset

The dataset contains astronomical observations collected from sky surveys.

### Features

#### Numerical Features

* alpha
* delta
* u
* g
* r
* i
* z
* redshift
* MJD

#### Categorical Features

* spectral_type
* galaxy_population

### Target Variable

* STAR
* GALAXY
* QSO

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Checked missing values
* Examined class distribution
* Visualized feature distributions
* Identified correlations among numerical variables

### 2. Data Preprocessing

* Separated numerical and categorical features
* Applied label/ordinal encoding to categorical variables
* Handled missing values
* Prepared train-validation splits

### 3. Feature Engineering

* Encoded categorical variables
* Evaluated feature importance
* Removed unnecessary columns when applicable

### 4. Model Training

The following models were evaluated:

* Logistic Regression
* Random Forest
* XGBoost
* LightGBM (if used)

### 5. Validation Strategy

* Stratified Train-Test Split
* Cross Validation
* Balanced Accuracy evaluation metric

---

## Results

| Model               | Balanced Accuracy |
| ------------------- | ----------------- |
| Logistic Regression | XX.XX             |
| Random Forest       | XX.XX             |
| XGBoost             | 94.9%             |

Best Performing Model: **XGBoost**

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Repository Structure

```text
stellar-classification-kaggle/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── submission.csv
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/stellar-classification-kaggle.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebook.ipynb
```

---

## Competition

Kaggle Playground Series – Predicting Stellar Class

The goal is to accurately classify astronomical objects using observational features and machine learning techniques.

---


* AI Engineering

