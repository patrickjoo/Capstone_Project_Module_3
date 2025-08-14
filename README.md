# E-Commerce Customer Churn Prediction

## 📌 Project Overview
This project focuses on predicting customer churn for an e-commerce platform using machine learning. Churn prediction helps businesses retain valuable customers by identifying those at risk of leaving. By leveraging various customer attributes, we aim to build a predictive model that provides insights into churn patterns and improves customer retention strategies.

## 🗂 Dataset Information
The dataset used for this project contains various features related to customer behavior and engagement, including:
- **CityTier**: Customer's city classification
- **CouponUsed**: Number of coupons used by the customer
- **HourSpendOnApp**: Average hours spent on the application
- **CashbackAmount**: Cashback amount received by the customer
- **DaySinceLastOrder**: Number of days since the last order
- **MaritalStatus**: Marital status of the customer
- **Complain**: Whether the customer has made a complaint (1 = Yes, 0 = No)
- **Churn**: Target variable (1 = Churned, 0 = Not Churned)

## 🎯 Objectives
- Perform exploratory data analysis (EDA) to understand the dataset and detect patterns.
- Preprocess the data, including handling missing values, encoding categorical variables, and feature scaling.
- Train and evaluate various machine learning models for churn prediction.
- Interpret model performance using appropriate evaluation metrics.
- Provide actionable insights to improve customer retention.

## 🛠 Technologies Used
- **Python**
- **Pandas, NumPy** (Data Manipulation)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-Learn** (Machine Learning)
- **Jupyter Notebook** (Development Environment)

## 🚀 Project Workflow
1. **Data Preprocessing**
   - Handling missing values and duplicates
   - Encoding categorical variables
   - Scaling numerical features
   
2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions and correlations
   - Analyzing customer behavior patterns
   
3. **Model Training & Evaluation**
   - Training multiple models (Logistic Regression, Decision Tree, Random Forest, AdaBoost, etc.)
   - Evaluating models using accuracy, precision, recall, F1-score, and AUC-ROC
   
4. **Insights & Recommendations**
   - Understanding feature importance
   - Suggesting strategies to reduce churn

## 📊 Results & Insights
- The best-performing model achieved an accuracy of **XX%** with an AUC-ROC score of **XX**.
- Feature importance analysis highlighted that **CashbackAmount**, **HourSpendOnApp**, and **DaySinceLastOrder** had the most significant impact on churn.
- Customers with **low app engagement** and **longer days since last order** were more likely to churn, suggesting the need for improved re-engagement strategies.

## 📌 Future Improvements
- Fine-tuning hyperparameters to improve model accuracy.
- Experimenting with other advanced models such as XGBoost or LightGBM.
- Deploying the model as an API for real-time churn prediction.

## 📝 Conclusion
This project provides valuable insights into customer churn prediction, helping e-commerce businesses proactively retain customers. By leveraging machine learning, companies can implement targeted strategies to enhance customer satisfaction and reduce churn rates.

📧 **Email**: kerinmulianto@gmail.com
