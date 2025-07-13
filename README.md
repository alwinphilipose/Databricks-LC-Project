# Databricks-LC-Project

# 🧠 PySpark on Databricks – Step-by-Step Learning Notebook

This repository contains a hands-on Databricks notebook where all essential PySpark functions are explained one by one with real-world examples. The notebook is designed to help learners and data professionals understand how to work effectively with **Apache Spark using Python (PySpark)** in a **Databricks** environment.

---

## 📘 What's Inside

The notebook walks through practical examples of PySpark functionality, including:

### ✅ Data Ingestion
- Reading CSV and JSON files using `spark.read.format()`
- Using `.option("header", "true")` and `.option("inferSchema", "true")`

### ✅ Data Cleaning
- Handling null values using `dropna("any")` and `dropna("all")`
- Casting and formatting dates (`date_format`, `cast`, `try_cast`)

### ✅ Data Transformation
- Creating new columns using `withColumn`
- Applying functions like `col()`, `lit()`, `when()`, `expr()`

### ✅ Data Exploration & Display
- Using `.show()` and `display()` to view DataFrames in Databricks
- Visualizing and analyzing structured datasets

---

## 💻 Getting Started in Databricks

### Step 1: Upload the Notebook
1. Log in to your Databricks workspace
2. Click on `Workspace` → `Import`
3. Upload `Alwins Repo Team LC DATABRICKS.ipynb`

### Step 2: Attach to a Cluster
Make sure a running cluster is attached so the notebook can be executed.

### Step 3: Run the Notebook
Go through each cell sequentially. Each section is self-explanatory and builds on the previous one.

---

## 🛠 Requirements

While this notebook is designed for **Databricks**, you can also run the logic locally by installing:
