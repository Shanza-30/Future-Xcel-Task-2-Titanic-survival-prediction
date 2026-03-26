# 🚢 Titanic Survival Prediction – Machine Learning Project

## 📌 Project Overview

This project task 2 future xcel implements a complete **supervised machine learning pipeline** using the **Kaggle Titanic dataset**.

The goal is to predict passenger survival based on features such as **age, gender, passenger class, fare, and family relationships**.


## 📂 Dataset & Objective

- **Dataset:** Kaggle Titanic Dataset  
- **Target Variable:** `Survived`  
  - `0` = Did Not Survive  
  - `1` = Survived  
- **Problem Type:** Binary Classification  


## 🔍 Data Loading & Exploration

- Loaded and inspected dataset structure and data types  
- Checked missing values and data quality issues  
- Analyzed class distribution of the target variable  
- Identified important feature relationships using correlation analysis  



## 📊 Exploratory Data Analysis (EDA)

- Survival count plots to understand class balance  
- Age distribution histograms to observe passenger demographics  
- Correlation heatmaps to identify relationships between features and survival  


## 🧹 Data Preprocessing

- Handled missing values:
  - Age → Median value  
  - Embarked → Mode value  
- Removed noisy or irrelevant columns:
  - Name  
  - Ticket  
  - Cabin  
- Applied **one-hot encoding** to categorical features such as:
  - Sex  
  - Embarked  


## ✂️ Train-Test Split

- Split the dataset into training and validation sets  
- Ensured fair and unbiased evaluation of model performance  


## 🤖 Baseline Model

- Trained a **Logistic Regression** model as a baseline  
- Used it to establish an initial performance benchmark  


## 🌳 Improved Model

- Trained a **Random Forest Classifier** to capture complex patterns  
- Used **balanced class weights** to handle class imbalance  
- Extracted built-in **feature importance** scores  


## 📈 Model Evaluation

Models were evaluated using the following metrics:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

Additional evaluation techniques:
- Confusion matrix heatmaps  
- ROC curves  
- Cross-validation to assess model generalization  


## 🔎 Feature Importance & Interpretability

- Analyzed feature importance using Random Forest  
- Used **SHAP (SHapley Additive Explanations)** for detailed model interpretation  
- Identified key survival predictors such as:
  - Gender  
  - Passenger class  
  - Fare  


## ✅ Conclusion

- Demonstrates a complete **end-to-end machine learning workflow**  
- Covers data cleaning, visualization, model training, evaluation, and interpretation  
- Ideal for **beginner to intermediate learners** working on real-world classification problems  

