# ML--Bank-loan-classification

A machine learning project that predicts whether a personal loan will be approved based on customer demographics and financial data using Decision Tree classification and SMOTE for class balancing.

## 📌 Project Overview

The objective of this project is to analyze a dataset containing customer information and predict whether a personal loan will be approved. The analysis includes data visualization, feature insights, and machine learning using Decision Tree classification.


## 📊 Key Insights

- **Personal Loan Approval Rate:** Only a small percentage of customers receive loan approval.
- **Age and Income Trends:** Higher income and certain age ranges have a higher chance of approval.
- **Family Size Influence:** Families with 2–3 members are more likely to be approved.
- **Account Balance Factors:** Customers with higher credit card and average account balances had a higher approval probability.


## 🎯 Goal of the Project

- Explore the data using **Exploratory Data Analysis (EDA)**.
- Train a machine learning model to **predict loan approvals**.
- Use **SMOTE (Synthetic Minority Over-sampling Technique)** to handle class imbalance in the dataset.
- Evaluate the model performance using accuracy and classification reports.
  

## ⚙️ Tools & Technologies

- **Language:** Python
- **Libraries:** pandas, seaborn, matplotlib, scikit-learn, imbalanced-learn
- **Model Used:** Decision Tree Classifier


## 🚧 Challenges Faced

- **Class Imbalance:** Loan approval was rare in the dataset, requiring the use of SMOTE to synthetically balance the classes.
- **Feature Distribution:** Some features required transformation or deeper analysis to interpret correctly.
- **Overfitting Risk:** Decision Trees tend to overfit, so careful tuning is required.


## 📈 Future Improvements

- Try ensemble models like **Random Forest** or **Gradient Boosting** for better generalization.
- Include **feature scaling** and **hyperparameter tuning** for improved model performance.
- Build an **interactive dashboard** for real-time predictions.
