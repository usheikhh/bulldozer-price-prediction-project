# 🏗️ Bulldozer Price Prediction

A Jupyter Notebook-driven machine learning project to predict bulldozer sale prices using historical auction data. Implemented in Python with a rich set of data science libraries.


---

## 📋 Table of Contents

- [Project Overview](#-project-overview)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Features](#-features)  
- [Technologies](#-technologies)  

---

## 🧠 Project Overview

This repo contains a complete data science workflow:

- **Data loading & cleaning** — importing Kaggle’s Bluebook bulldozer dataset, handling missing values, converting datatypes, etc.  
- **Exploratory Data Analysis (EDA)** — inspecting data distributions, correlations, trends.  
- **Feature Engineering** — extracting features from sale dates, encoding categories, etc.  
- **Model Training** — regression via `RandomForestRegressor` (with optional experimentation on XGBoost).  
- **Evaluation** — using RMSLE (Root Mean Squared Log Error) to assess model performance.  
- **Visualizations/Insights** — charts showing feature importance, prediction vs actual, etc.

---

## 💻 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/usheikhh/bulldozer-price-prediction-project.git
   cd bulldozer-price-prediction-project
   ```

2. **(Optional) Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

Launch the notebook:
```bash
jupyter notebook end-to-end-bulldozer-price-regression.ipynb
```

Notebook walkthrough:

1. Import and pre-process the bulldozer dataset (Train/Valid/Test).  
2. Build a regression pipeline, train with cross-validation.  
3. Evaluate using RMSLE.  
4. Visualize performance and feature importance.  
5. Save or export trained model artifacts (e.g., via `joblib`).

---

## ✨ Features

- **Full regression pipeline** — from raw data to predictions  
- **Cleaned and engineered features** — date handling, categorical encoding  
- **Robust modeling** — Random Forest, optionally XGBoost  
- **Comprehensive evaluation** — RMSLE and model diagnostics  
- **Insightful visualizations** — charts and plots for deeper analysis  

---

## 🛠️ Technologies

- **Python** (3.8+)
- **Jupyter Notebook**
- **pandas**, **NumPy**
- **scikit-learn** (RandomForest, metrics)
- **matplotlib**, **seaborn**
- **joblib** (model persistence)

---

