# SC_ML_Task1

Machine Learning project for predicting house prices using Linear Regression Techniques.

## 📌 Project Overview
This project is part of my Machine Learning Internship (Task 1).  
The goal is to build a regression model that predicts house prices using the **Kaggle House Prices dataset**.

## 📂 Files in this Repository
- `HousePricePrediction.ipynb` → Google Colab notebook with code
- `README.md` → Project documentation

## 🛠️ Workflow
1. Data Preprocessing  
   - Handled missing values  
   - Encoded categorical variables  
   - Dropped `Id` column  
2. Models Used  
   - Linear Regression (baseline)  
   - Random Forest Regressor (final model)  
3. Evaluation Metrics  
   - MAE: ~17,500  
   - RMSE: ~26,000  
   - R²: ~0.84  

## 📊 Results
- Random Forest performed significantly better than Linear Regression.  
- Final predictions saved in `submission.csv`.  

## 🚀 Future Work
- Hyperparameter tuning  
- Feature engineering  
- Deployment as a web app (Streamlit/Flask)  



