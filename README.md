# 🧹 Data Cleaning with Python – Complete Practical Guide

## 📌 Overview

This notebook **DATA_CLEANING_WITH_PYTHON.ipynb** focuses on one of the most critical phases of Data Science — **Data Cleaning and Preprocessing**.

Real-world data is rarely clean. It often contains:
- Missing values  
- Duplicate records  
- Incorrect data types  
- Inconsistent entries  
- Outliers and noise  

This notebook demonstrates **how to identify, clean, and prepare raw data** using Python libraries so that it becomes suitable for **analysis, visualization, and machine learning models**.

---

## 🎯 Objective of This Notebook

The main objectives are:
- To understand **why data cleaning is important**
- To learn **step-by-step data preprocessing**
- To apply **Pandas and NumPy functions practically**
- To prepare data for **EDA and ML models**

---

## 🧠 Why Data Cleaning is Important

> “Garbage In = Garbage Out”

If data is not cleaned properly:
- Analysis becomes misleading
- Visualizations show wrong insights
- Machine learning models perform poorly

Data cleaning ensures:
- Accuracy  
- Consistency  
- Reliability  
- Better model performance  

---

## 🛠️ Libraries Used

### 📦 Pandas
Used for:
- Reading datasets
- Handling missing values
- Data manipulation
- Filtering and aggregation

### 📦 NumPy
Used for:
- Numerical operations
- Handling arrays
- Mathematical calculations

---

## 📥 Loading the Dataset

### `read_csv()`

```python
pd.read_csv("file.csv")
