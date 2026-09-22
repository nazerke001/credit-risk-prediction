# Credit Risk Prediction

#Project Overview
This project analyzes a credit risk dataset and uses machine learning to predict loan default.


# Dataset
The dataset contains information about borrowers and their loans, including:
- Age
- Income
- Employment length
- Loan amount
- Loan interest rate
- Loan grade
- Loan intent
- Credit history
- Loan status

The target variable is 'loan_status':
- '0' = did not default (people who paid their loan on time)
- '1' = defaulted (people who failed to repay their loan)

# Exploratory data analysis 
I explored the dataset to understand patterns related to loan default.

Some of the analysis included:

- Distribution of loan status
- Income and loan status
- Loan amount and loan status
- Loan intent and loan status
- Loan grade and loan status

# Data Preprocessing 
The data was prepared for machine learning using:
- Train/test split
- Median imputation for missing numerical values
- One-hot encoding for categorical variables

  

# Machine learning models
I trained and compared four classification models:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

 # Model Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- ROC-AUC
- ROC curves

The Random Forest model achieved an accuracy of **0.93** and an ROC-AUC of **0.93** on the test set.

# Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

# Conclusion

This project showed how exploratory data analysis and machine learning can be used to analyze credit risk and predict loan default.
