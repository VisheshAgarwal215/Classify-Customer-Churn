# Customer Churn Classification in Google Colab (Improved Version)

This project aims to predict customer churn using machine learning techniques. We use a logistic regression model to classify whether a customer will churn based on various features of the customer data.

The project is implemented in Google Colab, making it easy to run on any machine without requiring setup. The dataset is uploaded via Google Colab, and the model is trained and evaluated directly in the notebook.

## Project Overview

The customer churn dataset contains several features about each customer, such as their demographic information, account information, and service usage. Our goal is to predict if the customer will churn (`1`) or not (`0`).

### Key Steps:
1. **Data Importing**: Load and upload the dataset in CSV format.
2. **Data Cleaning**: Handle missing values and clean the data.
3. **Feature Engineering**: Encode categorical features and scale numerical features.
4. **Model Training**: Train a Logistic Regression model to classify churn.
5. **Model Evaluation**: Evaluate the model using classification metrics like accuracy and a detailed classification report.

## Files

- `customer_churn_classification.ipynb`: Jupyter notebook containing the complete code and analysis for customer churn classification.
- `requirements.txt`: A file containing all Python libraries required to run the notebook.

## Requirements

To run this project, you need to install the following Python packages:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- google-colab

You can install these libraries using `pip`:
```bash
pip install -r requirements.txt
