# telco-customer-churn-prediction

# 📊 Telco Customer Churn Prediction

## 📌 Overview

Customer churn prediction is an important problem for telecom companies. Losing customers directly affects revenue, so companies need tools to identify customers who are likely to leave.

This project builds a **machine learning model** that analyzes customer data and predicts whether a customer will **churn (leave the service)** or **stay with the company**.

By identifying churn patterns, businesses can take proactive actions to improve **customer retention and satisfaction**.

---

## ⚙️ Technologies Used

* 🐍 Python
* 📊 Pandas
* 🤖 Scikit-learn
* 📉 Matplotlib
* 📓 Jupyter Notebook

---

## 📂 Dataset

The dataset used in this project is the **Telco Customer Churn Dataset**.

It contains customer information such as:

* Customer demographics
* Internet service subscription
* Contract type
* Monthly charges
* Tenure (how long the customer stayed)
* Churn status

These features are used to train the model to predict whether a customer will leave the telecom service.

---

## 🔎 Project Workflow

The project follows a typical **machine learning pipeline**:

1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Model Training
6. Model Evaluation
7. Churn Prediction

---

## 📈 Results

The trained model analyzes customer attributes such as:

* Contract type
* Monthly charges
* Tenure
* Service subscriptions

Using these features, the model predicts the probability that a customer will churn.

This allows telecom companies to identify high-risk customers and implement strategies to reduce churn.

---

## 📁 Project Structure

```
telco-customer-churn-prediction
│
├── churn_model_test_notebook.ipynb
├── app.py.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Install the required libraries

```bash
pip install pandas scikit-learn matplotlib
```

### 2️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

### 3️⃣ Open the notebook

Run all cells to:

* analyze the dataset
* train the model
* generate churn predictions

