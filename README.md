📌 Project Overview

This project implements a complete supervised machine learning pipeline using the Kaggle Titanic dataset.

The goal is to predict passenger survival based on features like age, gender, class, fare, and family relationships.

📂 Dataset & Objective

Dataset: Kaggle Titanic Dataset

Target Variable: Survived (0 = No, 1 = Yes)

Problem Type: Binary Classification

🔍 Data Loading & Exploration

Loaded and inspected dataset structure, data types, and missing values.

Analyzed class distribution of the target variable.

Identified important feature relationships using correlation analysis.

📊 Exploratory Data Analysis (EDA)

Survival count plots to understand class balance.

Age distribution histograms to observe passenger demographics.

Correlation heatmaps to identify relationships between features and survival.

🧹 Data Preprocessing

Handled missing values in Age (median) and Embarked (mode).

Removed noisy or irrelevant columns: Name, Ticket, Cabin.

Applied one-hot encoding to categorical features like Sex and Embarked.

✂️ Train-Test Split

Split the dataset into training and validation sets.

Ensured fair and unbiased evaluation of model performance.

🤖 Baseline Model

Trained a Logistic Regression model as a baseline.

Used it to establish an initial performance benchmark.

🌳 Improved Model

Trained a Random Forest Classifier to capture complex patterns.

Used balanced class weights to handle class imbalance.

Extracted built-in feature importance scores.

📈 Model Evaluation

Evaluated models using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Visualized results using confusion matrix heatmaps and ROC curves.

Applied cross-validation to check model generalization.

🔎 Feature Importance & Interpretability

Analyzed feature importance using Random Forest.

Used SHAP (SHapley Additive Explanations) for detailed model interpretation.

Identified key survival predictors such as gender, passenger class, and fare.

✅ Conclusion

Demonstrates a full end-to-end ML workflow using Python and scikit-learn.

Covers data cleaning, visualization, model training, evaluation, and interpretation.

Ideal for beginner to intermediate learners working on real-world classification problems.
