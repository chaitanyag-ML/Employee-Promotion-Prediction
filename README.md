# Employee-Promotion-Prediction
Project Overview

This project predicts whether an employee is likely to be promoted based on historical HR data such as performance ratings, training scores, experience, and demographics.
It demonstrates a complete end-to-end machine learning pipeline, from data preprocessing to model evaluation and saving trained models.

**Problem Statement**

Organizations often struggle to identify employees eligible for promotion objectively.
This project uses machine learning to help HR teams make data-driven promotion decisions.

**Machine Learning Approach**

The project includes:
Data cleaning and preprocessing
Feature scaling and categorical encoding
Model training and comparison
Performance evaluation
Model persistence for deployment

**Technologies Used**

Programming Language: Python
Libraries:Pandas,NumPy,Scikit-learn,Joblib
**Tools:** Jupyter Notebook, Git

**Dataset Features**

Feature	                    Description
department	             Employee department
education	               Education level
gender	                 Gender
no_of_trainings	         Number of trainings attended
age	                     Employee age
previous_year_rating	   Performance rating
length_of_service	       Years in organization
avg_training_score	     Average training score
promotion	               Target variable (1 = Promoted, 0 = Not Promoted)

**Models Implemented**

Logistic Regression
Random Forest Classifier
Both models are evaluated and compared using standard classification metrics.

**Model Evaluation Metrics:** Accuracy, Precision, Recall, F1-score
Random Forest generally achieved higher performance due to its ability to handle non-linear relationships.
