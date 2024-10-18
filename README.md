# Titanic-Survival-Prediction
This repository contains a machine learning project aimed at predicting the survival of passengers aboard the Titanic using four different algorithms: Decision Tree, Random Forest, Logistic Regression, and Support Vector Machine (SVM).







Introduction: 

The Titanic dataset contains information about passengers aboard the ill-fated ship, including various features such as age, gender, ticket class, and more. The goal of this project is to predict whether a passenger survived based on these features.

Dataset Overview:

The dataset includes the following key features

![Screenshot 2024-10-18 194431](https://github.com/user-attachments/assets/97709e61-b0b5-4f7a-ae11-c1f2e1f64801)



Preprocessing Steps:

1. Handled missing values by filling them with the median (for numerical data) and mode (for categorical data).
2. Dropped irrelevant features such as PassengerId, Name, Ticket, and Cabin.
3. Encoded categorical variables like Sex and Embarked using one-hot encoding.

   
Algorithms Used:

1. Decision Tree
A Decision Tree model was implemented to classify the survival of passengers. This model is intuitive and easy to visualize.

2. Random Forest
The Random Forest algorithm, an ensemble of Decision Trees, was used to improve prediction accuracy and reduce overfitting.

3. Logistic Regression
Logistic Regression was applied as a baseline model to understand the linear relationships between the features and the target variable.

4. Support Vector Machine (SVM)
SVM was utilized for classification tasks, effective in high-dimensional spaces and for datasets where the number of dimensions exceeds the number of samples.


Installation:

To run this project, ensure you have the following libraries installed:

* pip install pandas scikit-learn

Usage:

Download the Titanic dataset from Kaggle or use local copies named train.csv and test.csv.
Run the Jupyter Notebook or Python script to execute the code.
Analyze the output and metrics for each model.


Results:

After evaluating the models, the following scores were achieved on Kaggle

Random Forest: 0.75837

Logistic Regression: 0.75837

Support Vector Machine (SVM): 0.75837

Decision Tree: 0.71531



Conclusion:

This project demonstrated the application of various algorithms for predicting Titanic passenger survival. By comparing their performance, we gained insights into their effectiveness and potential areas for improvement.
