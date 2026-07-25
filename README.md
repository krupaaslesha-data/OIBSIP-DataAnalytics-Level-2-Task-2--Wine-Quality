# OIBSIP-DataAnalytics-Level-2-Task-2--Wine-Quality

# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

This project predicts the quality of red wine based on its physicochemical properties using multiple machine learning classification algorithms. The objective is to compare the performance of different models and identify the most suitable one for predicting wine quality.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA) on the Wine Quality dataset.
* Analyze the distribution of wine quality scores.
* Study feature relationships using a correlation heatmap.
* Address class imbalance through feature engineering.
* Train multiple machine learning classification models.
* Compare model performance using evaluation metrics.
* Recommend the best model for deployment.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📂 Dataset

**Dataset:** Wine Quality (Red Wine)

The dataset contains physicochemical properties of wine samples, including:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality (Target Variable)

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

* Dataset inspection
* Missing value check
* Class distribution analysis
* Distribution plots for numerical features
* Correlation heatmap
* Class imbalance discussion

---

## ⚙️ Feature Engineering

Wine quality scores were converted into binary classes:

* Good Wine
* Bad Wine

This simplifies the classification problem and improves model performance.

---

## 🤖 Machine Learning Models

The following classifiers were trained and evaluated:

* Random Forest Classifier
* Stochastic Gradient Descent (SGD) Classifier
* Support Vector Classifier (SVC)

---

## 📈 Model Evaluation

Each model was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

A feature importance chart was generated for the Random Forest model.

A comparison table summarizes the performance of all three classifiers.

---

## 📌 Key Findings

* Alcohol content is one of the strongest indicators of wine quality.
* Volatile acidity negatively impacts wine quality.
* Random Forest provides better prediction performance than SGD and SVC.
* Class imbalance should be considered while building predictive models.

---

## 💡 Business Recommendations

1. Deploy the Random Forest model for production due to its high accuracy and robust performance.
2. Focus on controlling volatile acidity during wine production.
3. Improve alcohol balance and chemical composition to achieve higher-quality wine.
4. Continuously retrain the model with new production data for better prediction accuracy.

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run all notebook cells to reproduce the analysis and results.

---

## 📁 Project Structure

```text
Wine-Quality-Prediction/
│
├── Wine_Quality_Prediction.ipynb
├── winequality-red.csv
├── README.md
└── requirements.txt
```
