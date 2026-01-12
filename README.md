
This project implements a complete supervised machine learning workflow using the Kaggle Titanic dataset. The goal of the project is to predict whether a passenger survived the Titanic disaster based on personal and travel-related features such as age, gender, class, fare, and family relationships.

The workflow starts with loading and exploring the dataset to understand its structure, data types, and missing values. Basic exploratory data analysis is performed using visualizations such as count plots for the target variable, age distribution histograms, and correlation heatmaps to identify relationships between features and survival.

Data preprocessing is a major part of the project. Missing values in important columns like Age and Embarked are handled using statistical methods such as median and mode filling. Unnecessary or highly noisy columns such as Name, Ticket, and Cabin are removed. Categorical variables like Sex and Embarked are converted into numerical format using one-hot encoding so that machine learning models can process them correctly.

After preprocessing, the dataset is split into training and validation sets to allow fair evaluation of model performance. A baseline Logistic Regression model is trained first to establish a simple performance benchmark. This baseline helps in understanding how well a basic linear model can perform on the dataset.

To improve performance, a tree-based Random Forest model is then trained. This model is better at capturing complex relationships in the data and also provides built-in feature importance scores. Class imbalance is handled by using balanced class weights so that both survival and non-survival classes are treated fairly.

Model evaluation is done using multiple metrics, including accuracy, confusion matrix, precision, recall, and F1-score. Visualizations such as confusion matrix heatmaps and ROC curves are used to clearly understand how well the model performs. Cross-validation is also applied to check if the model generalizes well to different data splits and does not overfit to a single train-test split.

Feature importance is analyzed in two ways: using scikit-learn’s built-in feature importance from Random Forest and using SHAP (SHapley Additive exPlanations) for more detailed model interpretation. These methods help explain which features, such as gender, passenger class, and fare, have the strongest impact on survival predictions.

Overall, this project demonstrates an end-to-end supervised machine learning pipeline using Python and scikit-learn. It covers data loading, cleaning, visualization, model training, evaluation, interpretation, and validation. The project is suitable for beginners and intermediate learners who want to understand how to build and evaluate classification models in a real-world dataset.
