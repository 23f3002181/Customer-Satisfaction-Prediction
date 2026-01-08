📊 Customer Satisfaction Prediction using Machine Learning

📌 Project Overview

Customer satisfaction plays a critical role in the success of any organization. This project focuses on building a machine learning model to predict whether a customer is Satisfied or Not Satisfied based on customer support ticket data.

The project uses historical customer support tickets and applies data preprocessing, feature engineering, and supervised machine learning techniques to achieve high prediction accuracy.





🎯 Objective

To analyze customer support ticket data

To predict customer satisfaction as a binary outcome

To identify key factors influencing customer satisfaction

To build a model suitable for real-world business scenarios

🧠 Problem Formulation

Originally, customer satisfaction ratings were on a scale of 1 to 5, which led to poor performance in multi-class classification.
To improve results, the problem was reformulated as a binary classification task:

Rating	Label
1, 2, 3	Not Satisfied (0)
4, 5	Satisfied (1)

This approach significantly improved model accuracy and interpretability.

🗂️ Dataset Description

The dataset contains customer support tickets related to various technical products.

Key Features:

Customer Age

Customer Gender

Product Purchased

Ticket Type

Ticket Priority

Ticket Channel

First Response Time

Time to Resolution

Target Variable:

Satisfied (0 = Not Satisfied, 1 = Satisfied)

🛠️ Technologies Used

Programming Language: Python

Platform: Google Colab / Jupyter Notebook

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

🔄 Project Workflow

Data Loading

Exploratory Data Analysis (EDA)

Data Cleaning & Missing Value Handling

Feature Selection

One-Hot Encoding for Categorical Variables

Train-Test Split

Feature Scaling

Model Training using Gradient Boosting

Model Evaluation

Visualization & Insights

🤖 Machine Learning Model

Algorithm Used: Gradient Boosting Classifier

Reason for Selection:

Handles non-linear relationships well

Performs better on structured tabular data

Provides feature importance for interpretability

📈 Model Performance

Accuracy: ~75% – 85%

Evaluation Metrics:

Accuracy Score

Precision, Recall, F1-Score

Confusion Matrix

The binary classification approach significantly improved performance compared to multi-class classification.

🔍 Key Insights

Ticket Priority has a strong impact on customer satisfaction

Faster response and resolution times increase satisfaction

Ticket channel (Email, Chat, Phone) influences customer experience


📌 Future Enhancements

Use NLP techniques on ticket descriptions

Apply XGBoost / LightGBM for better performance

Deploy the model using Flask or Streamlit

Build a real-time customer satisfaction dashboard
