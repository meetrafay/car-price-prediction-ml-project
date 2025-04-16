# 🚗 Car Price Prediction — Machine Learning Project

## 📌 Overview
This project builds an end-to-end machine learning pipeline to predict car prices based on their specifications and features. The workflow covers everything from data loading to final model evaluation and includes detailed data preprocessing, EDA, outlier treatment, categorical encoding, and regression modeling.

---

## 📊 Problem Statement
Given a dataset of car specifications, the objective is to predict the selling price of a car using machine learning models and assess their performance.

---

## 📚 Technologies Used
- Python (Google colab Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels

---

## 📝 Workflow

1. **Data Exploration**
   - Checking for missing values, duplicates, data types
   - Initial inspection of data distribution

2. **Data Cleaning**
   - Handling missing values with mean/median/mode imputation
   - Removing duplicates and handling outliers using IQR capping
   - Converting garbage values like `?` into NaN and handling them

3. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions, relationships, and correlations
   - Analyzing categorical variables with boxplots and pie charts
   - Heatmap for correlation matrix

4. **Feature Engineering**
   - Dropping irrelevant or weakly correlated features
   - Encoding categorical variables using Label Encoding and One-Hot Encoding

5. **Model Building**
   - **Linear Regression**
   - **Decision Tree Regressor**
   - **Random Forest Regressor**
   - Model evaluation using R² Score and RMSE

6. **Feature Importance Analysis**
   - Interpreting Random Forest feature importance scores

---

## 📊 Results

| Model                  | R² Score | MSE  |
|:----------------------|:---------|:--------|
| Linear Regression       | 0.81 | 2848.45 |
| Decision Tree Regressor | 0.98 | 453805.25 |
| Random Forest Regressor | 0.99 | 274893.71 |

---

## 📈 Visualizations

Includes distribution plots, heatmaps, scatter plots, feature importance bar charts, and model prediction vs. actual comparisons.

---

## 📂 Files in This Repository

| File / Folder        | Description                            |
|:---------------------|:---------------------------------------|
| `car_price_prediction.ipynb` | Complete Google Colab Notebook with code, plots, and markdowns |
| `README.md`             | Project description and documentation |

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction-ml-project.git
   cd car-price-prediction-ml-project
