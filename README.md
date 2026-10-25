# CreditWise Loan System

A Machine Learning project that analyzes loan applicant data and predicts loan approval outcomes using Python and Scikit-learn. The project focuses on data cleaning, exploratory data analysis, feature engineering, classification models, and model evaluation.

## Project Overview

CreditWise Loan System uses applicant demographic, financial, employment, and credit-related information to predict whether a loan application is likely to be approved or rejected.

The project demonstrates an end-to-end machine learning workflow, from data preprocessing to model comparison and performance evaluation.

## Features

- Data loading and inspection using Pandas
- Data cleaning and missing value handling
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Categorical feature encoding
- Feature scaling and engineering
- Loan approval prediction using classification algorithms
- Model evaluation using standard classification metrics

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

The project will explore the following classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

The models can be compared before and after feature engineering to evaluate their effect on prediction performance.

## Dataset

The project uses `loan_approval_data.csv`, which contains information about loan applicants.

The dataset includes features such as:

- Applicant income and co-applicant income
- Age, gender, and marital status
- Employment status and education level
- Credit score and existing loans
- Debt-to-income ratio
- Savings and collateral value
- Loan amount and loan term
- Loan purpose and property area

The target variable is `Loan_Approved`, representing the loan approval outcome.

## Project Workflow

1. Load and inspect the dataset.
2. Identify and handle missing values.
3. Perform exploratory data analysis.
4. Visualize distributions and relationships between features.
5. Encode categorical variables.
6. Scale numerical features where required.
7. Perform feature engineering.
8. Train classification models.
9. Evaluate and compare model performance.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics help assess the models' ability to identify approved applications and distinguish between correct and incorrect predictions.

## Project Structure

```text
CreditWise_Loan_System/
│
├── credit_wise.ipynb
├── loan_approval_data.csv
├── dashboard.py
├── requirements.txt
└── README.md
```


Open the notebook and run the cells sequentially to reproduce the analysis and model training workflow.

## Learning Outcomes

Through this project, I will explore:

- Data preprocessing and cleaning
- Exploratory data analysis
- Data visualization
- Feature engineering
- Supervised machine learning
- Classification algorithms
- Model evaluation and comparison

## Future Improvements

- Hyperparameter tuning and cross-validation
- Testing additional classification algorithms
- Integrating explainable AI techniques
- Improving prediction performance
- Enhancing the interactive dashboard

## Author

**Fatimah Ajmal**

GitHub: [FatimaAjmal89](https://github.com/FatimaAjmal89)

## Disclaimer

This project is intended for educational and analytical purposes. Predictions should not be used as the sole basis for real-world lending decisions.
