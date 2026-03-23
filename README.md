# Car Price Prediction Model

A machine learning project that predicts car prices using linear regression, built with Python and Scikit-learn.

## Results
- **R² Score: 0.91** — the model explains 91% of the variance in car prices
- **Dataset:** 205 vehicles across 26 brands

## Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn (LinearRegression, train_test_split)
- Matplotlib, Seaborn

## What the Project Does
1. **Data Cleaning** — extracted brand names, removed irrelevant columns, checked for missing values
2. **Exploratory Analysis** — visualized average price by brand, MPG vs price, and fuel type vs price
3. **Preprocessing** — applied one-hot encoding to convert categorical features into numeric values
4. **Model Training** — trained a linear regression model on 80% of the data, tested on the remaining 20%
5. **Evaluation** — measured accuracy using R² score and Mean Squared Error

## Dataset
Uses the CarPrice Assignment dataset. You can download it from [Kaggle](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction).

## How to Run
1. Download the dataset and save it as `CarPrice_Assignment.csv` in the same folder
2. Open `car_price_prediction.ipynb` in Jupyter Notebook
3. Run all cells in order
