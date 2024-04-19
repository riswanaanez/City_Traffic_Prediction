# **City Traffic Prediction using Support Vector Machine**

This repository contains a machine learning model developed to predict city traffic using a supervised classification approach, specifically employing the Support Vector Machine (SVM) algorithm.

## **Project Overview**

City traffic prediction is crucial for urban planning, transportation management, and resource allocation. This project aims to provide accurate predictions of traffic levels in urban areas using machine learning techniques. The SVM algorithm is chosen for its ability to handle complex decision boundaries and high-dimensional data, making it suitable for this classification task.

## **Project Workflow**

1. Data Setup
-  Importing datasets containing relevant features such as time, weather conditions, speed, vehicle type, random event occured, energy consumption, and economic condition.
-  Essential libraries such as NymPy, Pandas, and scikit-learn (sklearn) are utilized for data manipulation and preprocessing

2. Data Cleaning and Encoding
-  Preprocessing the data to handle missing values, outliers, and categorical variables.
-  Encoding categorical variables using Label Encoding to prepare the data for model training.

3. Data Partitioning
-  Splitting the dataset into input features (X) and the target variable (y) representing traffic levels.
-  Ensuring that the data is properly partitioned to avoid data leakage and ensure unbiased model evaluation.

4. Train-Test Split
-  Dividing the dataset into training and testing sets to train the model on a subset of the data and evaluate its performance on unseen data.
-  Stratified sampling may be employed to maintain class balance across train and test sets, especially in the case of imbalanced datasets.

5. Normalization
-  Normalizing the input features using MinMaxScaler normalization technique to scale the feature values to a specific range (e.g., [0, 1]) for improved model convergence and performance.
  
6. Model Creation
-  Implementing the Support Vector Machine (SVM) algorithm for classification.

7. Performance Evaluation
-  Assessing model performance using various metrics such as confusion matrix, accuracy score, precision, recall, and F1-score.
-  Generating classification reports to provide insights into the model's predictive capabilities and performance across different traffic levels.
  
8. Graphical Representation
-  Visualizing the confusion matrix using Confusion Matrix Display to gain insights into the model's performance in predicting traffic levels across different classes.
  
## **Insight**

This model demonstrates exceptional accuracy, achieving a perfect accuracy score of 1.0, indicating precise predictions for city traffic levels. The comprehensive workflow ensures robust model training, evaluation, and interpretation, making it a valuable tool for urban planners, transportation authorities, and researchers.
