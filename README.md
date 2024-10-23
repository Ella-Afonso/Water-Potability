# Water Potability
Water Potability Prediction Project: Lifecycle of Machine Learning Project
Main Aim: The primary goal of this project is to predict whether water is potable (safe to drink) or not using machine learning (ML) and Auto ML techniques.

# 1) Problem Statement:
Contaminated water is a major issue worldwide, linked to several waterborne diseases. The objective of this project is to build a machine learning model that predicts the potability of water, determining whether it is safe for human consumption or not. By using ML and Auto ML algorithms, we aim to create a model that assists in real-time water quality assessments.

In this project:

We will build a classification model that predicts the potability of water using data on various water quality parameters (e.g., pH, hardness, solids).
This model can be utilized by water treatment facilities, environmental organizations, and health departments to make quick, data-driven decisions on water quality.

# 2) Data Collection:
The dataset includes several water quality parameters such as:

pH: Measures how acidic or basic the water is.
Hardness: Reflects the concentration of calcium and magnesium ions in water.
Solids: Total dissolved solids (TDS) present in the water.
Chloramines: Amount of chloramine used in the water treatment process.
Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity, Potability (target variable).

# 3) Exploratory Data Analysis (EDA):
The dataset undergoes analysis to understand its structure, distribution, and any anomalies. EDA helps in detecting outliers, missing values, and understanding relationships between variables.

Correlation Heatmap: Visualizes the relationship between variables, showing how strongly different water quality parameters correlate with each other. For example, a high correlation between 'Hardness' and 'Solids' suggests these variables move together.
Boxplots and Density Plots: Used to understand the distribution of key variables such as pH, hardness, solids, and chloramines. These help in identifying potential outliers in the data.
Scatter Matrix: Visualizes pairwise relationships between variables, helping to spot trends and patterns.

# 4) Data Cleaning and Preprocessing:
Handling missing values, removing outliers, and transforming the data for model training. This step includes scaling numerical features to ensure they are on the same range and encoding categorical features, if any.

# 5) Model Building:
Using machine learning techniques, we aim to build predictive models to classify water potability based on given features.

Machine Learning Algorithms:
Logistic Regression
Random Forest Classifier
Gradient Boosting Machines (GBM)
Decision Trees
Support Vector Machines (SVM)
Auto ML with H2O: Auto ML automates the process of selecting the best algorithm and hyperparameters, allowing non-experts to use machine learning effectively.

# 6) Model Evaluation:
Evaluating model performance using key metrics like accuracy, precision, recall, F1-score, and ROC-AUC. This allows us to compare the performance of different models and choose the best one for deployment.

Confusion Matrix: Helps visualize the performance of the classification model, showing true positives, true negatives, false positives, and false negatives.
ROC-AUC Curve: Measures the trade-off between true positive rate and false positive rate, giving insights into how well the model distinguishes between potable and non-potable water.
Test Accuracy Score: The model's test accuracy reflects how well the model generalizes to unseen data.
