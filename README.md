# 🚢 Titanic - Machine Learning from Disaster

## 📌 Project Overview
The Titanic Survival project is a classic binary classification challenge. The goal is to build a predictive model that determines whether a passenger survived the Titanic shipwreck based on features like age, gender, ticket class, and fare.

This project focuses on the full data science lifecycle: from data preprocessing and exploratory analysis to model benchmarking and evaluation.

## 📊 Dataset Description
The dataset used is the famous "Titanic - Machine Learning from Disaster" dataset from Kaggle.
* **Target Variable:** `Survived` (0 = No, 1 = Yes)
* **Key Features:**
    * `Pclass`: Ticket class (1st, 2nd, 3rd)
    * `Sex`: Passenger gender
    * `Age`: Passenger age (handled missing values using mean imputation)
    * `SibSp/Parch`: Number of family members aboard
    * `Fare`: Ticket price
    * `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Libraries:** * **Data Handling:** Pandas, NumPy
    * **Visualization:** Matplotlib, Seaborn
    * **Machine Learning:** Scikit-Learn

## 🧪 Model Performance & Comparison
I implemented and compared five different classification algorithms to determine the most accurate predictor.

| Model | Accuracy (%) |
| :--- | :--- |
| **Logistic Regression** | **79.01%** |
| **Support Vector Machine (SVM)** | **77.48%** |
| **K-Nearest Neighbors (KNN)** | **75.95%** |
| **Decision Tree** | **73.66%** |
| **Naive Bayes** | **73.66%** |

### Key Findings:
* **Logistic Regression** emerged as the top performer with ~79% accuracy.
* Feature engineering involved cleaning irrelevant "zero" columns and handling missing values in `Age` and `Embarked`.
* Correlation heatmaps were utilized to identify multi-collinearity between features.
