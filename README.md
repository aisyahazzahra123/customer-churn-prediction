📉 Customer Churn Prediction
📌 Problem Statement

Customer churn is a major challenge for many subscription-based businesses.
This project aims to predict whether a customer will churn (leave the service) based on their demographic information, service usage, and billing details, enabling businesses to take proactive retention actions.

📊 Dataset

Dataset: Telco Customer Churn

Records: ~7,000 customers

Target variable: Churn (Yes / No)

Features include:

Customer demographics

Contract type

Monthly charges

Service usage

⚙️ Methodology

Data Cleaning

Handled missing values

Converted data types

Feature Engineering

Dropped irrelevant features (e.g. customerID)

Encoded categorical variables

Modeling

Logistic Regression

Random Forest Classifier

Evaluation

Accuracy

Confusion Matrix

Precision, Recall, F1-score

Special focus on recall for churn class

📈 Model Results
Model	Accuracy	Key Notes
Logistic Regression	~82%	Better recall & interpretability
Random Forest	~79%	Strong on non-churn prediction

Logistic Regression performed better for identifying churn customers, making it more suitable for business use cases where missing churn customers is costly.

💡 Business Insights

Customers with month-to-month contracts are more likely to churn

Higher monthly charges are strongly correlated with churn

Improving recall helps businesses identify at-risk customers earlier, even if overall accuracy slightly decreases

📌 These insights can support:

Targeted retention campaigns

Personalized pricing or contract strategies

🛠️ Tools & Libraries

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook / Google Colab

