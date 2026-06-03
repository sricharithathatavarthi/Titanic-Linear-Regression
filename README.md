# Titanic-Linear-Regression
# Titanic Dataset - Linear Regression 🚢

This repository contains step-by-step tasks performed on the Titanic dataset using **Google Colab**.  
The goal is to preprocess the dataset and apply a **Linear Regression model** to predict passenger survival.

---

## 📂 Contents
- `Titanic-Dataset.csv` → Original dataset
- `Titanic-Regression.ipynb` → Colab notebook with preprocessing + regression
- `README.md` → This guide

---

## 🪜 Steps
1. **Import & Preprocess**  
   - Handle missing values (Age → median, Embarked → mode, drop Cabin)  
   - Encode categorical features (Sex, Embarked)  

2. **Train-Test Split**  
   - Split dataset into 80% train, 20% test  

3. **Linear Regression Model**  
   - Fit model using `sklearn.linear_model.LinearRegression`  
   - Predict survival probabilities  

4. **Evaluation**  
   - Metrics: MAE, MSE, R²  
   - Scatter plot of actual vs predicted survival  

5. **Interpretation**  
   - Coefficients show feature importance  

---

## ⚙️ How to Run
1. Open [Google Colab](https://colab.research.google.com/)  
2. Upload `Titanic-Dataset.csv`  
3. Run notebook `Titanic-Regression.ipynb` step by step  

---

## 🎯 Next Steps
- Try **Logistic Regression** (better for classification tasks)  
- Compare with Decision Trees or Random Forests  
- Tune hyperparameters for improved accuracy  

---

## 👩‍💻 Author
Created by **Charitha** — learning ML & AI step by step 🚀
