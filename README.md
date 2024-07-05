# PCDA-Captone-Project
**Title:** Credit Card Approval Prediction

**Project Overview:** Credit scorecards are a common risk control method in the financial industry. They use personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. This project aims to build a machine learning model to predict whether a credit card applicant is a 'good' or 'bad' client, aiding banks in their decision-making process.

**Objective:**
Build a predictive model: Develop a machine learning model to classify credit card applicants as either 'good' or 'bad' clients.
Data Analysis: Perform exploratory data analysis (EDA) to understand and preprocess the data.
Model Evaluation: Compare the performance and interpretability of different machine learning models.

**Hypotheses:**
Null Hypothesis (H0): The credit card applicant is a 'good' client. This means that, based on the available data and the trained model, there is no significant evidence to suggest that the applicant will default.
Alternative Hypothesis (H1): The credit card applicant is a 'bad' client. This means that there is significant evidence, based on the model, to suggest that the applicant will default.

**Data Sources:**
application_record.csv: Contains personal and demographic information about credit card applicants.
credit_record.csv: Contains monthly credit status information for each applicant.

**Data Cleaning:**
Handling Missing Values: Used forward fill to handle missing data ensuring no gaps were left.
Outlier Removal: Removed outliers using the IQR method for key columns.
Categorical Encoding: Applied label encoding to transform categorical variables into numerical values.
Handling Duplicates: Managed duplicate IDs to avoid conflicting predictions.

**Exploratory Data Analysis (EDA):**
Initial Exploration: Revealed essential patterns and distributions.
Data Preprocessing: Included data cleansing, handling outliers, feature engineering, correlation analysis, addressing data imbalance, and encoding categorical variables.

**Machine Learning Models:**
Implemented the following models for both binary and multi-class classification:
Logistic Regression
Random Forest
Support Vector Machine (SVM)
XGBoost

**Model Evaluation:**
Evaluated models using accuracy, precision, recall, and F1-score metrics.
