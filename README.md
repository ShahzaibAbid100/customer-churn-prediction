# customer-churn-prediction
Customer Churn Prediction using Logistic Regression and Machine Learning.
 Customer Churn Prediction

## 📌 Project Overview

This project uses Machine Learning to predict whether a customer will leave a company (churn) or continue using its services.

The project uses the **Telco Customer Churn dataset** and **Logistic Regression** for classification.

## 🎯 Objective

The main objective is to predict customer churn based on customer information such as:

- Customer tenure
- Monthly charges
- Total charges
- Contract type
- Internet service
- Payment method
- Senior citizen status
- Other customer service information

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab
- Logistic Regression

## 🤖 Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification.

In this project:

- `0` = Customer will stay
- `1` = Customer will churn

## 🔄 Project Workflow

1. Load the dataset
2. Explore the dataset
3. Check data types
4. Check missing values
5. Clean the data
6. Convert `TotalCharges` into numeric format
7. Handle missing values
8. Remove unnecessary columns
9. Encode categorical variables
10. Separate features (`X`) and target (`y`)
11. Split data into training and testing sets
12. Train Logistic Regression model
13. Make predictions
14. Evaluate the model
15. Predict churn for a new customer

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed `customerID`
- Converted `TotalCharges` to numeric
- Handled missing values
- Converted `Churn` into numerical values
- Used One-Hot Encoding for categorical variables

## 📊 Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

## 📁 Dataset

Dataset used:

**Telco Customer Churn Dataset**

The dataset contains information about customers and whether they left the company.

## 🚀 Prediction

After training the model, it can be used to predict whether a new customer is likely to churn.

Example:

```python
prediction = model.predict(new_customer)

print("Churn Prediction:", prediction[0])
