# Assignment_MLBS
**Heart Disease Risk Prediction**
Project Overview
This project focuses on predicting the 10-year risk of coronary heart disease (CHD) in patients. It utilizes machine learning models to analyze patient data and make predictions based on various features. The project involves exploratory data analysis, feature extraction using Principal Component Analysis (PCA), and model evaluation.

**Table of Contents
Introduction
Dataset
Exploratory Data Analysis
Feature Extraction
Machine Learning Models
Logistic Regression
Support Vector Machines (SVM)
Decision Trees
K-Nearest Neighbors (KNN)
Model Evaluation
Conclusion
Getting Started
Dependencies
Usage**
**Introduction**
Coronary heart disease (CHD) is a significant health concern, and predicting the risk of CHD in patients is crucial for early intervention and prevention. This project explores different machine learning models to predict the 10-year risk of CHD based on patient data.

**Dataset**
The dataset used for this project contains various patient attributes such as age, cholesterol levels, blood pressure, and more. It also includes a binary target variable indicating whether a patient is at risk of CHD within the next 10 years.

**Exploratory Data Analysis**
Exploratory data analysis (EDA) was performed to gain insights into the dataset. Visualizations and statistical analysis helped in understanding the distribution of features, identifying correlations, and detecting potential outliers.

**Feature Extraction**
Principal Component Analysis (PCA) was employed to extract relevant features from the dataset. This technique reduced the dimensionality of the data while retaining important information.

**Machine Learning Models**
Four machine learning models were evaluated for CHD risk prediction:

**Logistic Regression:** A simple and interpretable model known for its efficiency with linear relationships.

**Support Vector Machines (SVM):** A model capable of handling high-dimensional data and both linear and non-linear classification tasks.

**Decision Trees:** A model that can capture non-linear relationships but may be prone to overfitting.

**K-Nearest Neighbors (KNN)**: A model that can capture local patterns but can be computationally expensive.

**Model Evaluation**
Each model was evaluated using performance metrics such as accuracy, precision, recall, and F1-score. The strengths and weaknesses of each model were discussed to determine the most suitable model for CHD risk prediction.

**Conclusion**
Based on the evaluation, Logistic Regression was identified as the most suitable model for predicting CHD risk due to its high accuracy, efficiency, and balanced precision and recall scores.

**Getting Started**
To replicate this project, follow these steps:

Clone this repository to your local machine.
Install the required dependencies (see Dependencies).
Run the Jupyter Notebook or Python script to execute the project.
Dependencies
Ensure you have the following dependencies installed:

Python 3.x
Jupyter Notebook
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
You can install these dependencies using pip or conda.

Usage
Feel free to use this project as a reference for predicting CHD risk or adapt it for your own healthcare-related prediction tasks. Modify the dataset, feature engineering techniques, or machine learning models as needed for your specific use case.
