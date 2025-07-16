# Task2---predictive-analysis-using-machine-learning
# 🚀 Scalable Machine Learning with PySpark on Google Colab

## 📌 Project Objective

This project demonstrates how to:
- ✅ Analyze a **large dataset** using **Apache PySpark**
- ✅ Build a **machine learning classification model**
- ✅ Use **Google Colab** with no downloads required

We predict income categories using demographic features from a 100,000-row dataset.

---

## 🔧 Tools & Technologies

- [Google Colab](https://colab.research.google.com) – Cloud-based notebook
- **PySpark** – Big Data processing and MLlib for machine learning
- **Dataset** – Public CSV file of synthetic person data (~100,000 rows)

---

## 📁 Dataset

**URL:**  
`https://raw.githubusercontent.com/datablist/sample-csv-files/main/files/people/people-100000.csv`

**Features Used:**
- `age`
- `height`
- `weight`
- **Target:** `income` (to be predicted)

---

## 📘 Workflow Steps

### 1. Setup PySpark in Google Colab
```bash
!apt-get install openjdk-8-jdk-headless -qq > /dev/null
!pip install -q pyspark
