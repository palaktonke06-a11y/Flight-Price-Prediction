# ✈️ Flight Price Prediction

<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/7893/7893979.png" width="150">
</p>

<h1 align="center">✈️ Flight Price Prediction</h1>

<p align="center">
A Machine Learning project focused on predicting flight ticket prices using Python.
Features comprehensive data cleaning, exploratory data analysis (EDA), and feature engineering on historical flight data.
Implements regression models to accurately forecast prices based on airlines, departure times, stops, and routes to help users find the best deals.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![EDA](https://img.shields.io/badge/EDA-Exploratory%20Analysis-red)

</p>

---

## 📌 Project Overview

This project aims to predict flight ticket prices using Machine Learning techniques. Historical flight data is analyzed and preprocessed to identify important factors affecting ticket prices. Various features such as airline, source, destination, journey date, duration, and total stops are used to train regression models capable of forecasting flight fares.
### Dataset Information

- **Data_Train.csv** → Historical flight data used for training and analysis.
- **Test_set.csv** → Unseen flight data used for prediction and model evaluation.

---

## 🚀 Project Workflow

## 🤖 Model Pipeline

```text
📥 Raw Flight Data
        │
        ▼
🧹 Data Cleaning
        │
        ▼
🔧 Missing Value Handling
        │
        ▼
📅 Date & Time Feature Extraction
        │
        ▼
🔤 Categorical Encoding
   (One-Hot Encoding)
        │
        ▼
📊 Feature Selection
        │
        ▼
✂️ Train-Test Split
        │
        ▼
🤖 Model Training
        │
        ▼
💰 Flight Price Prediction
```


---

## 📂 Project Structure

```text
Flight-Price-Prediction/
│
├── Data_Train.csv
├── Test_set.csv
├── Flight_Price_Prediction.ipynb
└── README.md
```

---

## 📊 Exploratory Data Analysis (EDA)

The dataset was analyzed to understand the factors influencing flight ticket prices.

### Analysis Performed

* Airline-wise Price Analysis
* Source & Destination Analysis
* Journey Date Analysis
* Duration vs Price Relationship
* Total Stops Impact on Price
* Departure Time Analysis
* Arrival Time Analysis
* Correlation Analysis Between Features

---

## ⚙️ Feature Engineering

The following preprocessing and feature engineering steps were performed:

- Handled missing values.
- Extracted journey date features.
- Extracted departure and arrival hour/minute.
- Converted duration into usable numerical features.
- Encoded categorical variables using One-Hot Encoding.
- Prepared the dataset for machine learning model training.

---

## 🤖 Machine Learning Model

Regression techniques were used to predict flight prices based on historical data.

### Model Pipeline

```text
Data Preprocessing
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
        │
        ▼
Price Prediction
```

---

## ⭐ Key Highlights

* Cleaned and preprocessed real-world flight data.
* Handled missing values and categorical features.
* Performed detailed exploratory data analysis.
* Applied feature engineering techniques.
* Built regression-based machine learning models.
* Predicted flight ticket prices accurately.
* Evaluated model performance using standard regression metrics.

---

## 🛠️ Technologies Used

| Tool             | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| Pandas           | Data Manipulation         |
| NumPy            | Numerical Computing       |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Scikit-Learn     | Machine Learning          |
| Jupyter Notebook | Development Environment   |

---

## 📂 Dataset Information

| File           | Description                                           |
| -------------- | ----------------------------------------------------- |
| Data_Train.csv | Historical flight data used for training and analysis |
| Test_set.csv   | Unseen flight data used for testing and prediction    |

---

## 🚀 How to Run

```bash
git clone [https://github.com/palaktonke06-a11y/Flight-Price-Prediction.git]

cd Flight-Price-Prediction

jupyter notebook
```
