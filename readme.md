# ML House Price Prediction

This project focuses on predicting house prices using machine learning regression models.
The dataset used is the Boston Housing dataset from the UCI Machine Learning Repository.

---

# Dataset
The dataset contains 506 instances with 13 features related to housing attributes such as
crime rate, number of rooms, accessibility to highways, and property tax.
The target variable is **MEDV** (Median House Value).

---

# Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Models Used
- Linear Regression (baseline model)
- Decision Tree Regressor (max_depth = 5)
- Random Forest Regressor (100 estimators, max_depth = 10)
- Gradient Boosting Regressor (100 estimators, learning_rate = 0.1)

---

# Project Workflow
1. Data loading and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature selection and train-test split  
4. Model training with hyperparameter tuning  
5. Model evaluation using R², MAE, and MSE  

---

# Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

# How to Run the Project
```bash
pip install -r requirements.txt
jupyter notebook
