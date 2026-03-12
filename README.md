# Ad Click Prediction using XGBoost

## 📌 Project Overview

This project builds a Machine Learning classification model to predict whether a user will click on a digital advertisement.
The goal is to improve ad targeting, reduce wasted marketing spend, and increase conversion efficiency.

The model is trained using the XGBoost algorithm, which is known for high performance and scalability in real-world machine learning applications.

---

## 🎯 Problem Statement

Digital marketing companies often show ads to a large number of users, but not all users are interested.
Showing ads to the wrong audience increases cost and reduces campaign efficiency.

We want to build a model that predicts:

Clicked on Ad → Yes / No

This helps in:

* Better audience targeting
* Reduced ad cost
* Higher click-through rate (CTR)
* Improved ROI

---

## 📊 Dataset

Dataset used: Advertising Dataset (Kaggle)

Features:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Male
* Clicked on Ad (Target)

Target variable:
Clicked on Ad (0 = No, 1 = Yes)

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Joblib
* Streamlit (optional for deployment)

---

## 🧠 Machine Learning Approach

Steps followed in the project:

1. Problem Understanding
2. Data Loading
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Selection
6. Train-Test Split
7. Model Training using XGBoost
8. Model Evaluation (Accuracy, Precision)
9. Model Saving
10. Deployment Ready Structure

---

## 🤖 Model Used

XGBoost Classifier

Why XGBoost?

* High accuracy
* Handles complex data
* Works well with tabular datasets
* Widely used in industry
* Fast and scalable

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Confusion Matrix

Precision is important because wrong ad targeting increases marketing cost.

---

## 📂 Project Structure

ad-click-prediction-xgboost/

data/
advertising.csv

notebook/
model.ipynb

model/
xgb_model.pkl

app/
app.py

README.md
requirements.txt

---

## 🚀 How to Run

Install libraries

pip install pandas numpy scikit-learn xgboost streamlit joblib

Run notebook

Open model.ipynb

Run Streamlit app (optional)

streamlit run app.py

---

## 💼 Resume Description

Built a machine learning model using XGBoost to predict ad click behavior based on user demographics and activity data, improving targeting efficiency using classification metrics such as precision and accuracy.

---

## 🎤 Interview Explanation

This project predicts whether a user will click on an advertisement using demographic and behavioral data.
I used XGBoost because it provides high accuracy and works well on tabular datasets.
The goal was to improve ad targeting and reduce wasted ad spend.

---

## 📌 Future Improvements

* Hyperparameter tuning
* GridSearchCV
* Random Forest comparison
* Streamlit deployment
* Real-time prediction API

---

## 👤 Author

Harman Hora
