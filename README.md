# 🏠 Regression on Housing Dataset

This project demonstrates the application of multiple regression algorithms to a housing dataset. The goal is to predict housing prices based on various numerical features using different machine learning models.

---

## 📂 Dataset Overview

The dataset used contains multiple numerical features related to housing attributes such as:
- Number of rooms
- Property age
- Distance to employment centers
- Indexes related to socio-economic status

The target variable is the **housing price**.

---

## 🔧 Workflow

1. **Data Loading**
   - Load the housing dataset (embedded from sklearn or external CSV).

2. **Data Preprocessing**
   - Handle missing values using `SimpleImputer` with median strategy.
   - Standardize the features using `StandardScaler`.
   - Use `Pipeline` to automate preprocessing.

3. **Model Training**
   - Apply multiple regression models (listed below).
   - Fit the models on training data.

4. **Evaluation**
   - Evaluate models using:
     - Root Mean Squared Error (RMSE)
     - R² Score

5. **Comparison**
   - Compare results to identify the most accurate model.

---

## 🤖 Models Implemented | النماذج المستخدمة

The following regression models were applied and compared in this notebook:

- **LinearRegression**  
  Basic regression model without regularization.  
  نموذج الانحدار الأساسي بدون تنظيم.

- **SGDRegressor**  
  Stochastic Gradient Descent for linear models, suitable for large datasets.  
  نموذج الانحدار باستخدام الانحدار العشوائي التدرجي، مناسب للبيانات الكبيرة.

- **GradientBoostingRegressor**  
  Ensemble technique that builds multiple decision trees sequentially to reduce prediction error.  
  تقنية تجميع تبني عدة أشجار قرارات بشكل تسلسلي لتقليل الخطأ في التنبؤ.

- **XGBRegressor**  
  Optimized version of gradient boosting provided by the XGBoost library. Known for speed and high performance.  
  إصدار محسن من Gradient Boosting مقدم من مكتبة XGBoost، معروف بالسرعة والأداء العالي.

---

## 📊 Metrics Used

- **RMSE (Root Mean Squared Error)**: Measures average magnitude of error.
- **R² Score (Coefficient of Determination)**: Measures how well predictions match actual values.

---

## 📈 Results Summary

Each model was evaluated on both training and validation sets to assess generalization and prevent overfitting. The best model can be selected based on the lowest RMSE and highest R² Score.

---

## ✍️ Author
Ali Mohamed Ali Abdulwahed  
Faculty of Computer and Information Technology  
Egyptian University for E-Learning  
Data Science Track

---

## 📬 Contact
- [LinkedIn Profile](https://www.linkedin.com)
- Email: ali.example@email.com
