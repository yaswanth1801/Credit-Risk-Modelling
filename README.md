

# Credit Risk Modelling

##  Overview

This project focuses on predicting the probability of borrower default using machine learning techniques like logistic regression and light GBM(Gradient boosting model). By analyzing financial, demographic, and loan-related features, the model helps lenders assess risk more accurately and make data-driven lending decisions. 
Perfect 👍 Since your current **Credit Risk Modelling** README is very minimal, I’ll draft a **comprehensive README** that you can directly use in your GitHub repo. This will make your project more professional, attractive, and informative for others.


## Objectives

* Predict whether a loan applicant is likely to default.
* Identify important financial and demographic factors influencing credit risk.
* Compare multiple machine learning models for best performance.
* Deploy the model using **Flask API** for real-world application.



## Tech Stack

* **Programming Language**: Python
* **Libraries**: pandas, numpy, scikit-learn, LightGBM, matplotlib, seaborn
* **Model Deployment**: Flask
* **Model Persistence**: Joblib



## Project Structure

```
├── data/                # Raw and cleaned datasets
├── notebooks/           # Jupyter notebooks for EDA & model building
├── models/              # Trained ML models stored here
├── app.py               # Flask app for deployment
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```



## Methodology

1. **Data Collection** – Credit risk dataset with borrower demographics, loan amount, income, interest rates, etc.
2. **Data Preprocessing** – Handling missing values, outliers, feature encoding, and scaling.
3. **Exploratory Data Analysis (EDA)** – Identifying correlations, trends, and default patterns.
4. **Feature Engineering** – Creating derived variables like `loan_to_income_ratio`, `credit_utilization_rate`.
5. **Model Training** – Logistic Regression, Random Forest, and LightGBM were trained and tuned.
6. **Model Evaluation** – Compared using ROC-AUC, Accuracy, Precision, Recall, and F1-score.
7. **Deployment** – Final model deployed with Flask for real-time predictions.



## Results & Insights

* **LightGBM** achieved the best performance with a high ROC-AUC score.
* **Loan-to-income ratio** and **employment length** were strong predictors of default.
* The Flask app provides a user-friendly way to get real-time predictions for new applicants.
