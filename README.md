 Loan Approval Prediction

 Project Overview

This project predicts whether a loan application will be approved or rejected using machine learning. The project combines SQL data analysis with Python and machine learning techniques to analyze loan applications and build a prediction model.

 Objectives

- Analyze loan application data using SQL.
- Perform data preprocessing and exploratory data analysis.
- Identify factors that influence loan approval.
- Build a machine learning model to predict loan approval.
- Evaluate the model using Accuracy and ROC-AUC.
- Create a simple interface for loan approval prediction.

 Technologies Used

- Python
- Pandas
- Scikit-learn
- Random Forest
- SQL
- MySQL
- Google Colab
- Gradio
- GitHub
- Hugging Face

 Dataset

The dataset contains information about loan applicants, including:

- Age
- Gender
- Education
- Person Income
- Employee Experience
- Home Ownership
- Loan Amount
- Loan Intent
- Loan Interest Rate
- Loan Percentage
- Credit History
- Credit Score
- Previous Loan
- Loan Status

`Loan Status` is the target variable.

- `1` = Loan Approved
- `0` = Loan Not Approved

 SQL Analysis

SQL was used to analyze the loan dataset and obtain useful insights.

Some of the SQL analyses include:

- Total number of loan applications
- Approved and rejected applications
- Average credit score
- Average loan amount
- Loan approval rate
- Approval based on education
- Approval based on loan intent
- Average income of approved applicants
- Applicants with high credit scores

The SQL queries are available in:

`loan_approval_queries.sql`

 Machine Learning

A Random Forest Classifier was used to predict loan approval.

 Data Preprocessing

- Separated features and target variable.
- Converted categorical variables into numerical values using one-hot encoding.
- Split the dataset into training and testing sets.
- Used an 80:20 train-test split.

 Model

Random Forest Classifier

```python
RandomForestClassifier(
    n_estimators=100,
    random_state=42
)
