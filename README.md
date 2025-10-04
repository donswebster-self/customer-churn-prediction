# Credit Card User Churn Prediction

## 📌 Project Overview
This project applies advanced machine learning techniques to predict customer churn in the credit card industry. By identifying customers most likely to leave, financial institutions can take proactive retention measures and reduce revenue loss.

## 🎯 Objective
- Build predictive models that accurately classify high-risk churn segments.  
- Provide actionable insights for retention campaigns.  

## 🛠️ Tools & Technologies
- **Python 3**
- **Pandas**, **NumPy** for data processing
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for ML models and evaluation
- **imbalanced-learn** for handling class imbalance
- **XGBoost** for gradient boosting
- **Jupyter Notebook** for development and analysis

## 📂 Project Structure
``` 
customer_churn_prediction/
│── notebooks/
│   └── Credit_Card_Users_Churn_Prediction_FullCode_DonW.ipynb
│── report/
│   └── Credit_Card_User_Churn_Prediction_FullPage_Case_Study.pdf
│── requirements.txt
│── README.md
```

## 🔍 Approach
1. **Data Preprocessing**  
   - Handled missing values, scaled numeric features, encoded categorical variables.  
2. **Exploratory Data Analysis (EDA)**  
   - Correlation analysis and identification of key churn drivers.  
3. **Model Training**  
   - Logistic Regression, Decision Trees, Random Forest, Gradient Boosting (XGBoost).  
4. **Hyperparameter Tuning**  
   - GridSearchCV applied to optimize model performance.  
5. **Evaluation**  
   - Accuracy, Precision, Recall, F1-Score, ROC-AUC.  

## 📊 Results
- Best model: **XGBoost**  
- ROC-AUC: **~0.85** with balanced precision and recall  
- Successfully identified high-risk churn segments.  

## 💡 Business Value
This model provides financial institutions with data-driven insight into customer behavior, enabling:  
- Prioritization of at-risk customer segments.  
- Focused retention campaigns.  
- Reduced revenue leakage.  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook notebooks/Credit_Card_Users_Churn_Prediction_FullCode_DonW.ipynb
   ```

