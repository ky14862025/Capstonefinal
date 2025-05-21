# Capstonefinal


# Insider Threat Detection Using Machine Learning

This project focuses on the development of a machine learning model to detect insider threats based on behavioral activity logs. It uses real-world inspired datasets, such as the **CERT Insider Threat Dataset**, and applies various preprocessing and modeling techniques to identify anomalous or risky behavior patterns among users.

## 📌 Objective

To build an automated system that can analyze user activity logs and detect potential insider threats using machine learning techniques.

---


## 📊 Dataset

The notebook is designed to work with activity logs typically available in insider threat datasets. These logs can include:

* User logins/logouts
* File access and movement
* Email and web activity
* Device usage patterns
* User and system metadata

> 💡 **Note**: The dataset is assumed to be pre-loaded or downloaded externally due to potential license restrictions on CERT data.

---

## 🔧 Technologies Used

* **Python 3.x**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Scikit-learn** – ML models and preprocessing
* **Matplotlib / Seaborn** (optional) – visualization

---

## 🔍 Workflow Overview

1. **Data Loading**

   * Reads CSV/TSV formatted activity logs into pandas DataFrames.

2. **Data Preprocessing**

   * Handles missing values
   * Encodes categorical variables
   * Normalizes or standardizes features

3. **Exploratory Data Analysis (EDA)**

   * Displays sample data entries using `.head()`
   * Investigates distributions and correlations

4. **Model Development**

   * Classification models (e.g., Random Forest, Logistic Regression) are trained to identify risky behavior
   * Evaluation using metrics like accuracy, precision, recall, and F1-score

5. **Prediction & Evaluation**

   * Model tested on unseen data
   * Potential output includes threat classifications or risk scores

---




## 📈 Results & Future Work

* Early results suggest the model can learn to detect anomalies based on activity patterns.
* Further improvements can include:

  * Deep learning techniques (e.g., LSTM for time-series logs)
  * Graph-based anomaly detection
  * Real-time log streaming and alerting

---

## 📌 Notes

* Ensure the dataset is in the correct format and preprocessed before feeding into the model.
* Be cautious with class imbalance: insider threat cases are often rare.

---




