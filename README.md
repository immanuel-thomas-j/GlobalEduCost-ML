# 🌍 GlobalEduCost ML

A machine learning model to predict the cost of studying abroad using international education data.

---

## 📘 Project Overview
This project estimates various educational and living costs for students planning to study abroad.  
The model is trained on a dataset containing tuition fees, rent, visa fees, insurance costs, and more from universities worldwide.

---

## 🎯 Features
- Country, City, University  
- Program, Degree Level, Duration (in years)  
- Tuition (USD), Rent (USD), Visa Fee (USD), Insurance (USD)  
- Living Cost Index, Exchange Rate

---

## 🤖 Model
- Multi-output regression using **Linear Regression** wrapped in `MultiOutputRegressor`  
- Predicts multiple target variables simultaneously:
  - Tuition Cost (USD)  
  - Living Cost Index (USD)  
  - Visa Fee (USD)  
  - Insurance Cost (USD)

---

## 🔧 How to Use
1. Download the dataset from Kaggle.  
2. Load and clean the dataset.  
3. Train and evaluate the model using the provided notebook.  
4. Use the trained model to predict international study costs.

---

## 📈 Results
The model achieved an R-squared value of **0.935**, indicating strong predictive performance.  
Feature engineering and outlier handling (Winsorization) helped improve the model from an initial R² of 0.64.

---

## 🚀 Future Work
- Try advanced regressors (Random Forest, XGBoost)  
- Add more data sources or features (e.g., country-specific scholarships)  
- Build a web-based cost estimator app

---

## 🧑‍💻 Author
**Immanuel Thomas J**

---

## 📂 Dataset Source  
Made using dataset from [Kaggle – Cost of International Education](https://www.kaggle.com/datasets/adilshamim8/cost-of-international-education)
