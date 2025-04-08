# 📈 Advertisement Budget Prediction

This project analyzes the impact of advertisement budgets across different media channels—**TV, Radio, and Newspaper**—on product **Sales**. Multiple regression models were built, evaluated, and compared to identify the best predictive approach. The dataset was sourced from Kaggle.

---

## 🧠 Objective

- Understand the relationship between advertisement spending and sales performance.
- Build predictive models to forecast sales based on ad budgets.
- Evaluate and compare model performance using R², RMSE, and other metrics.

---

## 📦 Dataset

- **Source**: [Kaggle - Advertising Dataset](https://www.kaggle.com/)
- **Features**: 
  - TV Advertising Budget
  - Radio Advertising Budget
  - Newspaper Advertising Budget
- **Target**: Sales (in thousands of units)

---

## 🔍 Workflow

1. **Data Exploration**  
   - Checked dataset shape, data types, missing values, and duplicates.
2. **Exploratory Data Analysis (EDA)**  
   - Plotted distributions, boxplots, and pairplots to analyze relationships.
3. **Preprocessing**  
   - Removed outliers using IQR method  
   - Standardized features using `StandardScaler`
4. **Modeling**  
   - Implemented:  
     - Linear Regression  
     - Ridge Regression  
     - Lasso Regression  
     - ElasticNet Regression  
     - Polynomial Regression (up to degree 5)
5. **Evaluation**  
   - Metrics: R² Score, MSE, RMSE  
   - Visualized predictions vs actuals  
   - Residual plots for model diagnostics

---

## 🚀 Best Model

- **Polynomial Regression (Degree 5)**  
  - 📌 **Train R²**: 0.997  
  - 📌 **Test R²**: 0.995  
  - 📉 **Test RMSE**: ~0.33

---

## 🧰 Technologies Used

- Python (Pandas, Numpy, Matplotlib, Seaborn)
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

## 📊 Key Insights

- **TV and Radio** ad budgets strongly influence sales.
- **Newspaper** budget has minimal correlation with sales.
- Polynomial regression significantly improves predictive accuracy.

---

## 📁 Folder Structure


