# Preventing Customer Churn with Feature Transformation

## 📖 Project Overview
The objective of this project is to predict customer churn by applying feature transformation and engineering techniques to enhance the performance of machine learning models.  
The project demonstrates the process of data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## 📊 Dataset
The dataset contains customer-level information, including demographics, account details, and service usage. The target variable is **Churn** (Yes/No).

## 🔍 Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Identified distributions, correlations, and class imbalance.  
   - Visualized churn rates across demographics and services.

2. **Feature Engineering & Selection**  
   - Created new features from existing columns.  
   - Applied encoding for categorical variables.  
   - Normalized continuous variables.  
   - Evaluated feature importance using tree-based models.

3. **Modeling**  
   - Baseline model: Logistic Regression with minimal preprocessing.  
   - Enhanced model: Logistic Regression + Feature Engineering.  
   - Advanced models: Random Forest, XGBoost.  

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, and **F1-score** with focus on the **Churn** class.  
   - Performance comparison across baseline and improved models.

## 📈 Results
- The enhanced models outperformed the baseline.  
- Feature engineering (e.g., tenure grouping, service bundling) improved predictive power.  
- Tree-based models highlighted the most important features (tenure, monthly charges, contract type).

## 📝 Summary of Findings
See the final section inside the notebook for a detailed markdown summary.
