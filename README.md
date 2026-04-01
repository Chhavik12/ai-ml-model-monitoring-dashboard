# 🚀 AI/ML Model Monitoring Dashboard

## 📌 Project Overview

This project builds an end-to-end Machine Learning monitoring system for a sentiment analysis model using movie reviews.
Instead of evaluating the model once, the system simulates real-world conditions by monitoring performance over time.

---

## 🎯 Objectives

* Perform sentiment analysis on movie reviews
* Compare multiple ML models
* Monitor model performance over time
* Detect data drift and behavioral changes
* Track model confidence for reliability

---

## 🧠 Features

* ✅ NLP-based sentiment classification (TF-IDF)
* ✅ Model comparison (Logistic Regression vs Naive Bayes)
* ✅ Batch-wise performance tracking (simulating real-time data)
* ✅ Data drift detection
* ✅ Prediction behavior analysis
* ✅ Model confidence monitoring
* ✅ Interactive Power BI dashboard

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy, Scikit-learn)
* **NLP** (TF-IDF Vectorization)
* **Power BI** (Dashboard Visualization)

---

## 📊 Dashboard Overview

### 🔹 Page 1: Model Performance

Tracks accuracy, precision, recall, and F1 score over time.

### 🔹 Page 2: Data Drift Monitoring

Analyzes changes in data distribution and identifies drift patterns.

### 🔹 Page 3: Sentiment Behavior

Monitors prediction trends and detects potential bias in model outputs.

### 🔹 Page 4: Confidence Monitoring

Tracks model confidence to identify uncertainty in predictions.

---

## 📁 Project Structure

```
ai-ml-model-monitoring-dashboard/
│
├── data/
│   ├── raw/              # (Not included due to size)
│   ├── processed/
│   │   └── monitoring_data.csv
│
├── notebooks/
│   ├── data_processing.ipynb
│   ├── merge_dataset.ipynb
│
├── dashboard/
│   └── ai_model_monitor.pbix
│   └── ai_model_monitor_dashboard.pdf
│
├── README.md
├── requirements.txt
```

---

## 📂 Dataset Note

Due to size limitations, the original dataset is not included in this repository.

You can download the dataset from:
👉 https://www.kaggle.com/datasets/mantri7/imdb-movie-reviews-dataset

---

## 🚀 How to Run the Project

1. Clone the repository
2. Open the notebooks folder
3. Run preprocessing and model training
4. Use the generated `monitoring_data.csv`
5. Load it into Power BI dashboard

---

## 🎯 Key Insights

* Logistic Regression outperforms Naive Bayes across all evaluation metrics
* Model performance remains stable across batches
* No significant data drift observed
* Model confidence remains consistent, indicating reliable predictions

---

## 🧠 Learning Outcomes

* Understanding of real-world ML monitoring systems
* Hands-on experience with NLP and model evaluation
* Knowledge of data drift and model behavior tracking
* Dashboard development using Power BI

---

## ⭐ Conclusion

This project goes beyond traditional ML by implementing a complete monitoring pipeline, similar to real-world production systems. It demonstrates strong understanding of MLOps concepts and practical deployment considerations.

---

## 👩‍💻 Author

**Chhavi Kamboj**

---
