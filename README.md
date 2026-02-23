# 🌍 Air Quality Prediction & Analysis

## 📌 Project Overview

This project analyzes air pollution data in Indian cities and builds a machine learning model to classify air quality levels (AQI Bucket).
The workflow includes data cleaning, feature engineering, visualization, and classification using ensemble models.

---

## 🎯 Objectives

* Clean and preprocess real-world air quality data
* Handle missing values intelligently
* Engineer meaningful pollution features
* Explore pollution patterns across cities
* Build a robust multi-class classification model
* Evaluate performance using standard metrics

---

## 📊 Dataset

* **Source:** Kaggle – Air Quality Data in India
* **Records:** ~29K rows
* **Features:** Pollutant measurements + AQI labels
* **Target:** `AQI_Bucket`

---

## 🧹 Data Preprocessing

Key steps performed:

* Removed rows with missing target
* Filled missing values using **class-wise median imputation**
* Converted date to datetime
* Encoded categorical variables
* Handled class imbalance using **class weights**

---

## 🧠 Feature Engineering

Created aggregated pollution indicators:

* **Vehicular Pollution Content**
* **Industrial Pollution Content**

This helped capture pollution sources more effectively.

---

## 📈 Exploratory Data Analysis

Performed multiple visual analyses:

* Most vs least polluted cities
* Top 10 cities by AQI
* Pollution trends over time
* Correlation heatmap
* Feature importance using Decision Tree

✅ Key insight: noticeable pollution drop during 2020 lockdown period.

---

## 🤖 Modeling

### Models Used

* Decision Tree (for feature importance)
* Random Forest (final model)

### Train/Test Split

* 80% Training
* 20% Testing

---

## 🏆 Results

**Random Forest Performance**

* ✅ Accuracy: **94.78%**
* 📊 Strong precision and recall across classes
* ⚖️ Class imbalance handled successfully

---

## 🧰 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn
* Matplotlib & Seaborn
* Plotly
* XGBoost (imported)

---

## 🚀 How to Run

```bash
# Install requirements
pip install -r requirements.txt

# Run notebook or script
python main.py
```

---

## 📁 Project Structure (suggested)

```
Air-Quality-Analysis/
│
├── data/
├── notebooks/
├── images/
├── clean_city_day.csv
├── requirements.txt
└── README.md
```

---

## 🔮 Future Work

* Deploy model with FastAPI
* Add time-series forecasting
* Try deep learning models
* Build interactive dashboard

---

## 💡 Author

**Mayada Mahmoud Shaban**
Data Science & AI Enthusiast 🚀
