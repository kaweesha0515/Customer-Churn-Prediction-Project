
# Telco Customer Churn Prediction

## 📌 Project Overview
This project focuses on predicting customer churn in the telecommunications sector using a logistic regression model. The dataset used is the **Telco Customer Churn Dataset**, which contains information about customer demographics, services, and account details.

## 🚀 Key Features
- **Data Preprocessing**: Cleaned and transformed categorical and numerical variables for effective modeling.
- **Exploratory Data Analysis (EDA)**: Analyzed churn trends and feature importance.
- **Feature Engineering**: Converted categorical features into numerical representations using one-hot encoding.
- **Machine Learning Model**: Implemented logistic regression for churn prediction.
- **Performance Evaluation**: Assessed model performance using probability predictions and accuracy calculations.
- **Real-Time Prediction**: Tested model predictions on new customer data.

## 📂 Dataset Information
- **Source**: WA_Fn-UseC_-Telco-Customer-Churn.csv
- **Target Variable**: `churn` (Binary: 1 - Churn, 0 - No Churn)
- **Features**:
  - Categorical: `gender`, `contract`, `internetservice`, `paymentmethod`, etc.
  - Numerical: `tenure`, `monthlycharges`, `totalcharges`

## 🔧 Tech Stack
- **Python** (pandas, numpy, seaborn, matplotlib, scikit-learn)
- **Machine Learning**: Logistic Regression
- **Feature Processing**: DictVectorizer for categorical encoding
- **Visualization**: Seaborn & Matplotlib

## 📊 Model Training & Evaluation
- **Data Splitting**: 80% Training, 20% Testing
- **Model Used**: Logistic Regression (`liblinear` solver)
- **Feature Selection**: Used mutual information scores
- **Performance Metrics**:
  - Probability predictions
  - Accuracy evaluation
  - Feature importance extraction

📌 Future Enhancements

Implement more advanced models (Random Forest, XGBoost, Neural Networks)

Improve feature selection and engineering

Deploy as a web app using Flask or FastAPI

✨ Contributions are welcome! Feel free to fork, enhance, and submit pull requests. 🚀

