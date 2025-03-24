# Mentalhealth_ETL_Pipeline
# 🧠 Mental Health Data Pipeline with PySpark

## 🚀 Project Overview
This project uses PySpark on Databricks to clean, transform, and analyze a real-world mental health dataset from Kaggle. It simulates a complete data engineering workflow including:

- Data ingestion
- Data cleaning and normalization
- Feature engineering
- Encoding categorical variables
- Writing partitioned Parquet files
- Analytical queries using Spark SQL

---

## 📊 Dataset

**Kaggle Link:**  
[Anxiety and Depression: Mental Health Factors](https://www.kaggle.com/datasets/ak0212/anxiety-and-depression-mental-health-factors)

---

## 🛠️ Tech Stack
- Apache Spark (PySpark)
- Databricks Community Edition
- Parquet file format
- GitHub for version control

---

## 🧪 Features Created
- `Total_Mental_Health_Score` = Anxiety + Depression + Stress
- `High_Stress_Flag` = binary indicator for high stress
- `Gender_Code` = encoded gender values (0: Male, 1: Female, etc.)

---

## 💾 Output
The processed data is saved in partitioned Parquet format:
