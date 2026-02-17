# Flipkart-Customer-Satisfaction-Prediction
Flipkart Customer Satisfaction Prediction (Machine Learning)
🧠 Project Overview

This project builds a machine learning model to predict whether a customer will be satisfied or dissatisfied based on customer support interaction data from Flipkart.

Predicting satisfaction helps businesses improve service quality, reduce churn, and enhance customer experience.

🎯 Problem Statement

The goal is to predict customer satisfaction using CSAT scores.

Satisfied → CSAT ≥ 4

Unsatisfied → CSAT ≤ 3

This is treated as a binary classification problem.

📂 Dataset Description

85,907 customer support interactions

20 features including:

✔ Communication channel
✔ Issue category & sub-category
✔ Agent details & tenure
✔ Shift timing
✔ Product information
✔ CSAT Score (1–5)

⚙️ Methodology

Data Cleaning & Preprocessing

Handling Missing Values

Feature Engineering

Label Encoding of categorical variables

Train-Test Split (80:20)

Model Training — Random Forest Classifier

📈 Model Performance

Accuracy: 81.3%

Key influential features:

Issue category

Sub-category

Channel name

Agent shift

Tenure bucket

💼 Business Impact

This model enables organizations to:

✔ Identify dissatisfied customers early
✔ Provide proactive support
✔ Optimize agent allocation
✔ Improve customer experience
✔ Reduce churn

🚀 Future Scope

NLP sentiment analysis on customer remarks

Advanced models (XGBoost, Neural Networks)

Real-time prediction system

Integration into customer support dashboards

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

▶️ How to Run

Clone the repository

Install dependencies

Place dataset in project folder

Run the notebook

👤 Author
Shailendra Sharma

Shailendra Sharma
