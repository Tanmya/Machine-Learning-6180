# Credit Card Fraud Detection System

This project implements a credit card fraud detection system in Python, using various machine learning algorithms to identify and flag potentially fraudulent transactions. The system includes a dataset cleaning and pre-processing step, followed by the creation of an anomaly detection system using machine learning algorithms like neural networks, decision trees, and GridSearchCV.

# Installation

To use this project, you will need to have Python 3 installed on your system. You can download the latest version of Python from the official Python website. Additionally, you will need to install the following Python packages:

numpy
pandas
scikit-learn
tensorflow

You can install these packages using the pip command:

Copy code
pip install numpy pandas scikit-learn tensorflow

# Usage

To use the credit card fraud detection system, you will need to provide a dataset of credit card transactions. The system expects a CSV file with the following columns:

29965 ROWS X 24 COLUMNS

INDEPENDENT VARIABLES -
LIMIT_BAL: Amount of the given credit;
SEX: Gender (1 = male; 2 = female);
EDUCATION: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others);
MARRIAGE: Marital status (1 = married; 2 = single; 3 = others);
AGE: Age (year);
pay_1 to pay_6 : the repayment status;
BILL_AMT1 to bill_amt6: Amount of bill statement;
PAY_AMT1 to pay_amt6: Amount of previous payment;

DEPENDENT VARIABLE-
dpnm:Default payment next month.(Yes = 1, No = 0) 

Once you have your dataset, you can run the detect_fraud.py script to analyze the data and identify potential fraud. The script will output a CSV file with the results of the analysis, including a flag indicating whether each transaction is classified as fraudulent or not.

# Contributing

If you would like to contribute to this project, please submit a pull request with your proposed changes. Before submitting your pull request, please make sure that your changes are thoroughly tested and documented.

# Acknowledgements

This project was inspired by the work of researchers in the field of credit card fraud detection, and builds upon their contributions to this important area of study.
