````markdown
# 📊 Customer Churn Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🚀 Overview

Customer churn prediction is one of the most critical business problems in the telecommunications industry. Acquiring a new customer is significantly more expensive than retaining an existing one. This project applies Machine Learning techniques to predict whether a customer is likely to churn based on customer demographics, subscription details, billing information, and service usage.

The project follows a complete Data Science workflow including Exploratory Data Analysis (EDA), Data Preprocessing, Feature Engineering, Model Building, Hyperparameter Tuning, and Model Evaluation.

---

## 📁 Dataset

The project uses the **IBM Telco Customer Churn Dataset**.

- **Source:** Kaggle
- **Records:** 7,043 Customers
- **Features:** 21
- **Target Variable:** `Churn`

📥 **Dataset Link:**  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values
- Encode categorical variables
- Scale numerical features
- Train multiple Machine Learning models
- Compare model performance
- Identify the key factors affecting customer churn

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project includes:

- Customer Churn Distribution
- Correlation Heatmap
- Feature Relationship Analysis
- Scatter Plots
- Missing Value Analysis
- Feature Importance Analysis

---

## ⚙️ Data Preprocessing

- KNN Imputation for Missing Values
- Label Encoding
- Feature Scaling using StandardScaler
- Train-Test Split (80:20)

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost

Hyperparameter tuning was performed using **GridSearchCV**.

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **81.76%** |
| Random Forest | 80.55% |
| XGBoost | 80.46% |
| SVM | 80.41% |
| KNN | 75.51% |

🏆 **Best Model:** Logistic Regression

---

## 📌 Key Business Insights

- Month-to-Month contracts have the highest churn rate.
- Customers with shorter tenure are more likely to leave.
- Online Security and Tech Support significantly improve customer retention.
- Contract Type is the most influential feature for churn prediction.


## 📷 Sample Visualizations

- Churn Distribution
- Correlation Heatmap
- Feature Importance
- Confusion Matrix
- Model Accuracy Comparison

> *(Add screenshots of these graphs here after uploading them to GitHub.)*

---

## 🚀 Future Improvements

- Deploy the model using Streamlit
- Implement SMOTE for class balancing
- Build a REST API using Flask/FastAPI
- Real-time churn prediction
- Improve explainability with SHAP and LIME

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/rushigirdhari/Customer-Churn-Prediction.git
```

Move into the project directory

```bash
cd Customer-Churn-Prediction
```

Install the required packages

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📚 Libraries Used

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
shap
```

---

## 👨‍💻 Author

**Rushikesh Girdhari**

🎓 B.Tech Artificial Intelligence & Machine Learning  
📍 Symbiosis Institute of Technology, Pune

### Connect with Me

- GitHub: https://github.com/rushigirdhari
- LinkedIn: https://www.linkedin.com/in/rushikesh-girdhari-3642b9321/

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It motivates me to build and share more Data Science and Machine Learning projects!
````
