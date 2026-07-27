# Churn-Prediction-using-XGBoost
🚀 An end-to-end Machine Learning solution using XGBoost to predict customer attrition. Features advanced hyperparameter tuning and class imbalance handling, engineered specifically to optimize business retention metrics.

# 📊 Customer Churn Prediction Model using XGBoost

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fizramilanol/Churn-Prediction-using-XGBoost/blob/main/Churn_Analysis.ipynb)
[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org)
[![Framework](https://img.shields.io/badge/ML-XGBoost-orange.svg)](https://xgboost.readthedocs.io/)

## 📌 Project Overview
Retaining an existing customer is significantly cheaper than acquiring a new one. This project delivers a robust **Predictive Analytics Solution** designed to forecast customer attrition (*churn*) before it happens. 

By leveraging **XGBoost**, this model uncovers complex, non-linear patterns in customer behavior, empowering retention teams to launch proactive, targeted loyalty campaigns and safeguard company revenue.

---

## ⚡ Key Highlights & Business Impact
* **Imbalance Resolution:** Mitigated severe class imbalance to ensure the model accurately flags minority-class churners.
* **Business-Centric Optimization:** Tuned specifically to maximize the **Recall** metric, minimizing costly false negatives (undetected churn).
* **Actionable Insights:** Features built-in feature importance tracking to identify the primary operational drivers behind customer departure.

---

## 📊 Dataset Focus
The model ingests multi-dimensional customer data, including:
* **Demographics & Account Profile:** Tenure, contract structures, and payment methods.
* **Usage Dynamics:** Monthly charges, total accumulated spend, and service types.
* **Customer Behavior:** Frequency of customer service interactions (a critical churn indicator).

---

## 🚀 How to Run This Project (Quick Start)

This project was built entirely within **Google Colab** using a **Google Drive** storage architecture mapped to `"/content/drive/My Drive/Colab Notebooks"`. 

To run this notebook seamlessly, choose one of the options below:

### Option A: Standard Google Drive Mapping (Recommended)
1. Click the **Open In Colab** badge above or upload `churn_prediction.ipynb` directly to your Colab workspace.
2. Run the initialization cell to **Mount your Google Drive**.
3. Create a folder named exactly **`Colab Notebooks`** in your root Google Drive directory.
4. Upload the **`dataset.csv`** file from this repository into that folder.
5. Execute the cells sequentially.

### Option B: Zero-Setup Local Upload
1. Run the `Mount Drive` cell as usual.
2. Locate the environment variable path in the early cells:
   ```python
   folder_name = "/content/drive/My Drive/Colab Notebooks"

## 🛠️ Data Science Workflow
1. Exploratory Data Analysis (EDA): Uncovering statistical anomalies, correlations, and behavior trends among churned vs. active accounts.
2. Feature Engineering & Preprocessing: Handling missing values, transforming categorical structures via optimal encoding, and scaling numerical features.
3. Advanced Modeling: Training a robust baseline model, followed by fine-grained hyperparameter optimization (max_depth, learning_rate, n_estimators) via search cross-validation.
4. Evaluation Matrix: Evaluation anchored heavily on Recall and ROC-AUC to align technical performance with real-world business objectives.

## 💻 Tech Stack
1. Core Environment: Google Colab / Jupyter Notebooks
2. Language: Python
3. Machine Learning & Frameworks: XGBoost, Scikit-Learn
4. Data Manipulation & Visualization: Pandas, NumPy, Matplotlib, Seaborn
