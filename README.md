# Insurance-Prediction

This mini-project focuses on predicting insurance charges based on various factors such as age, BMI, smoking habits, and more using supervised machine learning models. The project was developed as part of our Artificial Intelligence & Machine Learning coursework.

## 📂 Project Overview

The goal of this project is to analyze a dataset containing insurance-related details and develop a regression model that accurately predicts the *insurance charges* for individuals. This helps insurance companies in estimating premiums and assessing customer profiles.

---

## 📊 Dataset

- *File*: insurance.csv
- *Source*: Kaggle / Publicly Available Dataset
- *Attributes*:
  - age: Age of the primary beneficiary
  - sex: Gender (male/female)
  - bmi: Body mass index
  - children: Number of children covered by health insurance
  - smoker: Smoking status (yes/no)
  - region: Residential region (northeast, southeast, southwest, northwest)
  - charges: Individual medical costs billed by health insurance (target)

---

## ⚙️ Tools & Technologies

- *Language*: Python 🐍
- *Environment*: Jupyter Notebook (.ipynb)
- *Libraries Used*:
  - pandas, numpy for data manipulation
  - matplotlib, seaborn for data visualization
  - scikit-learn for machine learning algorithms
  - LabelEncoder, LinearRegression, RandomForestRegressor etc.

---

## 📈 Approach

1. *Data Cleaning & Preprocessing*  
   - Handle categorical values using LabelEncoder
   - Check and handle missing values (if any)
   - Visualize features using plots

2. *Feature Selection & Engineering*  
   - Correlation heatmaps
   - One-hot encoding for region and smoker status

3. *Model Building*  
   - Used multiple regression models including:
     - Linear Regression
     - Random Forest Regressor
     - Gradient Boosting Regressor (optional)

4. *Model Evaluation*  
   - Used R² Score and Mean Squared Error (MSE) to evaluate model performance
   - Visual comparison between predicted vs actual values

---

## 📌 Results

- The *Random Forest Regressor* gave the most accurate predictions among the tested models.
- Feature importance showed *smoker* and *bmi* to be significant predictors of insurance charges.
