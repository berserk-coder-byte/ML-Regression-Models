# Regression and Classification ML Projects

This repository contains two machine learning projects:

1. **Boston House Price Prediction** using Linear Regression
2. **Sonar Rock vs Mine Classification** using Logistic Regression

Each project demonstrates a fundamental machine learning approach — regression for continuous outcomes and classification for binary categories.

---

## 🏡 1. Boston House Price Prediction

- **Model Used:** Linear Regression
- **Dataset:** Boston Housing Dataset (from kaggle via opendatasets)
- **Objective:** Predict the median value of owner-occupied homes in $1000s (target: `MEDV`)
- **Features:**
  - `CRIM`: Per capita crime rate by town
  - `ZN`: Proportion of residential land zoned for large lots
  - `INDUS`: Proportion of non-retail business acres per town
  - `CHAS`: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
  - `NOX`: Nitric oxide concentration (parts per 10 million)
  - `RM`: Average number of rooms per dwelling
  - `AGE`: Proportion of owner-occupied units built before 1940
  - `DIS`: Weighted distances to five Boston employment centers
  - `RAD`: Index of accessibility to radial highways
  - `TAX`: Full-value property tax rate per $10,000
  - `PTRATIO`: Pupil-teacher ratio by town
  - `B`: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
  - `LSTAT`: % lower status of the population
- **Evaluation Metric:** Mean Squared Error (MSE), R² Score
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

---

## 🌊 2. Sonar Rock vs Mine Classification

- **Model Used:** Logistic Regression
- **Dataset:** Sonar Dataset (Rock vs. Mine Classification)
- **Objective:** Classify sonar signals as either reflecting off a metal cylinder (mine) or a rock.
- **Features:**
  - 60 numerical features representing the energy of sonar signals returned at various frequencies
- **Target:** `R` (Rock) or `M` (Mine)
- **Evaluation Metrics:**
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-Score
- **Libraries:** `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ml-regression-classification.git
   cd ml-regression-classification
