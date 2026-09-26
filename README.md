# 📊 Customer Churn Prediction

## 📌 Project Overview

Customer Churn Prediction is a machine learning project that analyzes
customer information and predicts whether a customer is likely to leave
a service.

The project uses Exploratory Data Analysis, data preprocessing, and
Logistic Regression to build a binary classification model.

---

## 🎯 Objectives

- Analyze customer churn patterns
- Explore important customer characteristics
- Preprocess customer data
- Build a churn prediction model
- Evaluate model performance
- Identify important features related to churn
- Generate useful business insights

---

## 📊 Dataset

The project uses a Telco Customer Churn dataset containing customer
demographic, service, account, and billing information.

### Dataset Information

- Customer service information
- Contract details
- Tenure
- Monthly charges
- Total charges
- Churn status

The target variable is:

**Churn**
- Yes → Customer churned
- No → Customer stayed

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Logistic Regression

---

## 🔍 Project Workflow

### 1. Data Loading
The customer churn dataset was loaded using Pandas.

### 2. Exploratory Data Analysis
Customer churn distribution and relationships between churn and
different customer attributes were analyzed.

### 3. Data Preprocessing
- Converted `TotalCharges` into numeric format
- Handled missing values
- Removed the `customerID` column
- Converted categorical variables using one-hot encoding
- Scaled features using StandardScaler

### 4. Model Building
A Logistic Regression model was trained to predict customer churn.

### 5. Model Evaluation
The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 6. Feature Analysis
Logistic Regression coefficients were analyzed to identify features
that contributed more strongly to the model's predictions.

---

## 📈 Model Evaluation

The model performance was evaluated using the test dataset.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The exact results are available in the project notebook.

---

## 💡 Business Insights

Customer churn analysis can help businesses:

- Identify customers at higher risk of churn
- Understand customer behavior
- Develop customer retention strategies
- Improve service offerings
- Design targeted retention campaigns
- Make data-driven business decisions

---

## 📊 Visualizations

The project includes visualizations for:

- Customer Churn Distribution
- Churn Rate by Contract Type
- Tenure Distribution
- Monthly Charges by Churn
- Feature Importance
- Confusion Matrix

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```
---

## 📌 Conclusion

This project demonstrates how machine learning can be used to predict
customer churn and analyze customer behavior.

A Logistic Regression model was developed after performing data
preprocessing and exploratory analysis.

The resulting insights can help businesses understand churn patterns
and support data-driven customer retention strategies.

---

## 👩‍💻 Author

Kalpna Singh

Aspiring Data Analyst | Python | Data Analytics | Power BI | Excel
