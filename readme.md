# 🏡 Boston House Price Prediction

This project is a machine learning regression model that predicts housing prices in Boston based on a variety of economic and structural features. It's built using the classic Boston Housing dataset and serves as a great introduction to regression problems in machine learning.

## 📌 Project Overview

The objective is to build a predictive model that estimates the median value of owner-occupied homes (`MEDV`) in Boston suburbs. The model is trained using historical data with features such as crime rate, number of rooms, and access to highways.

## 🚀 Tech Stack

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Project Structure

boston-house-prediction/
│── data            # Raw dataset files (optional if using sklearn)
│├──housing.data
│├──housing.names
│
├── notebooks             # Jupyter Notebooks for EDA, modeling, usage, testing
├── 01_Real_Estate_EDA.ipynb
├── 02_Model_Testing.ipynb
├── 03_Model_Usage.ipynb
│
├── models                # Saved trained models
├── Real estate.joblib
│
├── requirements.txt        # List of dependencies
├── README.md               # Project overview and instructions
└── .gitignore              # Ignore checkpoints, model files, etc.



## 📊 Dataset Features

- `CRIM`: Crime rate per capita
- `ZN`: Residential land zoned for large lots
- `INDUS`: Non-retail business acres
- `NOX`: Nitric oxide concentration
- `RM`: Average rooms per dwelling
- `AGE`: Proportion of old buildings
- `DIS`: Distance to employment centers
- `RAD`: Highway access index
- `TAX`: Property tax rate
- `PTRATIO`: Pupil-teacher ratio
- `B`: Proportion of Black population
- `LSTAT`: % lower status population
- `MEDV`: Median home value (Target)

## 🧠 ML Workflow

1. Data Loading and Exploration
2. Feature Analysis and Visualization
3. Train-Test Split
4. Model Training (e.g., Linear Regression, Random Forest)
5. Cross-Validation and Evaluation
6. Model Saving

## 📈 Model Evaluation

The model was evaluated using cross-validation. Below are the RMSE scores:

Scores: [2.91446165, 2.86115048, 4.23816164, 2.65273827, 3.48167687, 2.71400131,
4.54123406, 3.29201743, 3.60162183, 3.02993575]

Mean RMSE: 3.33
Standard Deviation: 0.61


> A lower RMSE indicates better predictive performance.

## 📦 Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/leviosa2002/boston-house-prediction.git
cd real-estate-prediction
pip install -r requirements.txt
