![Project Banner](banner.png)
# 🚀 Scalable E-commerce Data Analysis and Revenue Prediction using Apache Spark

## 📌 Overview

This project focuses on analyzing large-scale e-commerce data and predicting revenue using **Apache Spark (PySpark)**.
It demonstrates how big data technologies can be used to extract insights and build scalable machine learning models.

---

## 🎯 Objective

* Perform large-scale data analysis on e-commerce transactions
* Generate business insights (sales trends, top products, etc.)
* Build a machine learning model to predict **total sales (revenue)**
* Handle data efficiently using distributed computing (Spark)

---

## 🛠️ Tech Stack

* **Apache Spark (PySpark)**
* **Spark MLlib**
* **Python**
* **Big Data Processing**
* **Machine Learning (Regression Models)**

---

## 📂 Dataset

The dataset contains e-commerce transaction details such as:

* Order details (order_id, order_date, delivery_date)
* Customer details (customer_id, city, state)
* Product details (category, sub_category, brand)
* Pricing (unit_price, discount, shipping_cost)
* Target variable: **total_sales**

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Removed null values and duplicates
* Converted date columns
* Cleaned and structured the dataset

### 2️⃣ Feature Engineering

* Created `delivery_days` feature
* Extracted `month` and `year` from order date
* Added derived metrics for better prediction

### 3️⃣ Exploratory Data Analysis (EDA)

* Total revenue calculation
* Category-wise sales analysis
* Top-selling products identification

### 4️⃣ Model Building

* Used **Random Forest Regressor**
* Built using Spark ML Pipeline
* Handled categorical data using StringIndexer

### 5️⃣ Model Evaluation

* Evaluated using:

  * RMSE (Root Mean Squared Error)
  * R² Score

---

## 🤖 Machine Learning Model

**Model Used:** Random Forest Regressor

**Why Random Forest?**

* Handles large datasets efficiently
* Reduces overfitting
* Provides better accuracy for complex data

---

## 📊 Results

* Successfully predicted **total_sales (revenue)**
* Identified key factors affecting sales
* Achieved scalable performance using Spark

---

## 📈 Key Insights

* Certain categories generate higher revenue
* Discounts significantly impact sales
* Delivery time influences customer behavior

---

## 🚀 How to Run

```bash
# Start Spark
pyspark

# Run notebook or script
python main.py
```

---

## 💡 Future Enhancements

* Use **XGBoost / Gradient Boosting**
* Add real-time streaming data (Spark Streaming)
* Deploy model using Flask / API
* Build dashboard using Power BI / Tableau

---

## ⭐ Project Highlights (For Recruiters)

✔ Big Data Project using Spark
✔ End-to-End ML Pipeline
✔ Real-world Dataset
✔ Scalable Architecture
✔ Industry-relevant skills

---

## 📢 Conclusion

This project demonstrates how **big data analytics and machine learning** can be combined to generate valuable business insights and accurate revenue predictions in an e-commerce environment.

----
