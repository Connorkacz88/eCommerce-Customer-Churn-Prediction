# eCommerce-Customer-Churn-Prediction


## 📖 Project Overview
This project analyzes customer behavior in an eCommerce dataset to predict **churn likelihood** — identifying customers who are likely to stop purchasing or engaging with the platform.  
The goal is to help businesses improve **customer retention** and design **data-driven marketing strategies**.

---

##  Key Steps

### 1. Data Preprocessing
- Handled missing values using `SimpleImputer`
- Encoded categorical variables with `OneHotEncoder`
- Scaled numerical features using `StandardScaler`
- Combined transformations with a `ColumnTransformer` pipeline

### 2. Feature Engineering
- Created time-based and behavioral metrics (Recency, Frequency, Monetary)
- Engineered customer activity and engagement variables

### 3. Model Building
- Split data into training/testing sets with `train_test_split`
- Built ML pipelines using algorithms such as:
  - Logistic Regression  
  - Random Forest  
  - Gradient Boosting  
- Tuned hyperparameters and evaluated model performance

### 4. Evaluation
- Measured **Accuracy**, **Precision**, **Recall**, and **ROC-AUC**
- Visualized performance using confusion matrices and ROC curves

---

## Tools & Technologies
| Category | Tools |
|-----------|--------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

##  Results Summary
The best-performing model effectively identified high-risk customers, achieving strong predictive accuracy.  
These insights can help marketing and retention teams **target at-risk users** and improve overall customer lifetime value.

---


   git clone https://github.com/yourusername/ecommerce_churn_project.git
   cd ecommerce_churn_project
