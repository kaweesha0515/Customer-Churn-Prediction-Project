# 📞 Telco Customer Churn Prediction

## 📌 Project Overview
This project aims to predict **customer churn** in the telecommunications sector using **logistic regression**. By analyzing customer demographics, service usage patterns, and account details, the model identifies which customers are at risk of leaving.

## 🚀 Key Features
- 🔍 **Exploratory Data Analysis (EDA):** Identified churn patterns, visualized key metrics, and studied feature relationships.
- 🧹 **Data Preprocessing:** Cleaned and transformed both categorical and numerical features for effective modeling.
- 🧠 **Feature Engineering:** Applied **one-hot encoding** using `DictVectorizer` to handle categorical variables.
- 🤖 **Machine Learning Model:** Used **Logistic Regression** with the `liblinear` solver.
- 📊 **Model Evaluation:** Measured performance through probability scores, accuracy, and feature importance.
- ⚡ **Real-Time Predictions:** Tested the model with new customer data to evaluate predictive capabilities.

## 📂 Dataset Information
- **Source:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Target Variable:** `Churn` (Binary: `Yes` → 1, `No` → 0)

### 🔢 Features
- **Categorical:** `gender`, `contract`, `internetservice`, `paymentmethod`, etc.
- **Numerical:** `tenure`, `monthlycharges`, `totalcharges`

## 🔧 Tech Stack
- **Language:** Python
- **Libraries:** 
  - `pandas`, `numpy` – Data manipulation
  - `seaborn`, `matplotlib` – Visualization
  - `scikit-learn` – Machine learning and preprocessing

## 📊 Model Training & Evaluation
- **Data Split:** 80% training / 20% testing
- **Model:** Logistic Regression (`liblinear` solver)
- **Feature Selection:** Mutual information scores for relevance
- **Performance Metrics:**
  - Probability predictions
  - Accuracy scoring
  - Feature importance visualization

## 🔮 Future Enhancements
- 🧪 Experiment with advanced models: `Random Forest`, `XGBoost`, and `Neural Networks`
- 🧠 Improve feature selection and transformation pipelines
- 🌐 Deploy as an interactive web app using `Flask` or `FastAPI`

## 🤝 Contributions
✨ Contributions are welcome! Feel free to fork this project, enhance it, and submit a pull request.

## 📬 Contact
📧 **Email:** kaweeshawickrama@gmail.com

---

> Predicting customer churn helps businesses retain valuable customers and improve service strategies. This project demonstrates how data-driven insights can guide decision-making in telecom industries.
