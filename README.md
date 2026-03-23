# churchdata
# 📊 Customer Churn Prediction Pipeline

## 🚀 Project Overview

This project focuses on building a complete **Machine Learning Pipeline** to predict customer churn.
Customer churn refers to customers who are likely to stop using a company's services.

The project covers **data preprocessing, feature engineering, model building, and pipeline creation**, making it highly relevant for both **academic learning and real-world applications**.

---

## 🎯 Objectives

* Predict whether a customer will churn or not
* Perform complete **data preprocessing**
* Apply multiple **encoding and scaling techniques**
* Engineer meaningful features from raw data
* Build and evaluate machine learning models
* Create an end-to-end **ML pipeline**

---

## 📂 Project Structure

```
Customer-Churn-ML/
│
├── churn_prediction_pipeline.ipynb   # Main notebook
├── churn_data.csv                   # Dataset
├── preprocessing_report.md          # Data preprocessing steps
├── feature_engineering_documentation.md
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Information

The dataset contains customer information such as:

* Demographics (Gender, Senior Citizen, etc.)
* Account details (Tenure, Contract type)
* Service usage (Internet, Phone, etc.)
* Billing information (Monthly Charges, Total Charges)
* Target variable: **Churn (Yes/No)**

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn

---

## 🔧 Data Preprocessing Steps

### ✅ 1. Handling Missing Values

* Converted `TotalCharges` to numeric
* Filled missing values using median

### ✅ 2. Encoding Techniques (3 Methods)

* Label Encoding (binary variables)
* One-Hot Encoding (categorical variables)
* Ordinal Encoding (ordered features)

### ✅ 3. Feature Scaling (2 Methods)

* Standard Scaling
* Min-Max Scaling

### ✅ 4. Outlier Detection

* IQR Method
* Z-score Method

---

## 🧠 Feature Engineering

Created new features to improve model performance:

* AvgCharges (Average charge per tenure)
* TenureGroup (Customer segmentation)
* ChargesPerTenure
* IsLongTerm (Loyalty indicator)
* ServiceCount
* EngagementScore

---

## 📌 Feature Selection

* Used **correlation analysis** to select important features
* Removed less relevant features to improve performance

---

## 🤖 Models Used

* Logistic Regression
* Random Forest Classifier

---

## 📈 Model Performance

* Logistic Regression Accuracy: ~ (update after running)
* Random Forest Accuracy: ~ (update after running)

---

## 🔄 Machine Learning Pipeline

Built an end-to-end pipeline using:

* Data Scaling
* Model Training

This ensures:

* Reproducibility
* Cleaner workflow
* Production readiness

---

## 🛠️ How to Run the Project

### Step 1: Clone the Repository

```
git clone https://github.com/your-username/customer-churn-ml.git
cd customer-churn-ml
```

### Step 2: Install Requirements

```
pip install -r requirements.txt
```

### Step 3: Run Notebook

```
jupyter notebook churn_prediction_pipeline.ipynb
```

---

## 📌 Key Learnings

* Importance of **data preprocessing in ML**
* Handling categorical and numerical data
* Feature engineering techniques
* Outlier detection methods
* Building scalable ML pipelines

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Advanced models (XGBoost, LightGBM)
* Deployment using Flask or Streamlit
* Real-time prediction system

---

## 👨‍💻 Author

**Lokesh Bainaboyana**
CSE Student | GATE 2026 Aspirant | ML Enthusiast

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!
