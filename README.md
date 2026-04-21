# 📊 TCS Stock Price Analysis & Forecasting using Machine Learning

## 🧠 Project Overview
This project presents an end-to-end data analysis and machine learning pipeline to analyze and predict stock prices of Tata Consultancy Services (TCS). It combines statistical analysis, data visualization, and predictive modeling to extract meaningful insights from historical stock data and forecast future trends.

The solution leverages both traditional machine learning (Linear Regression) and deep learning (LSTM) techniques to improve prediction accuracy for time-series financial data.

---

## 🎯 Objectives
- Perform in-depth analysis of TCS stock data
- Identify market trends and behavioral patterns
- Build predictive models for stock price forecasting
- Compare performance of ML vs Deep Learning approaches
- Generate actionable insights from financial data

---

## 📁 Dataset Details
The dataset consists of historical stock data with the following attributes:
- Date – Trading date  
- Open – Opening price  
- High – Highest price  
- Low – Lowest price  
- Close – Closing price  
- Volume – Number of shares traded  
- Dividends – Dividend distribution  
- Stock Splits – Stock split information  

---

## ⚙️ Tech Stack
- Language: Python  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras  
- Tools: Jupyter Notebook, VS Code  

---

## 🔄 Workflow

### 1. Data Preprocessing
- Handled missing values and inconsistencies  
- Converted data types for analysis  
- Sorted dataset chronologically  
- Treated outliers for stable modeling  

### 2. Exploratory Data Analysis (EDA)
- Time-series visualization of stock prices  
- Volume and trading activity analysis  
- Correlation analysis using heatmaps  
- Moving averages (short-term & long-term trends)  

### 3. Feature Engineering
- Extracted temporal features (Year, Month, Day, Day of Week)  
- Created lag features (previous day’s closing price)  
- Generated moving averages for trend detection  

### 4. Model Development

#### 🔹 Linear Regression
- Baseline model for prediction  
- Features: Open, High, Low, Volume, Lag features  
- Evaluation metrics: MSE, R² Score  

#### 🔹 LSTM (Deep Learning)
- Designed for time-series forecasting  
- Applied MinMax scaling  
- Built sequential neural network  
- Captures temporal dependencies in stock data  

---

## 📈 Key Insights
- Strong positive correlation between Open, High, Low, and Close prices  
- Volume shows relatively weaker influence on price movement  
- Moving averages effectively highlight trend shifts  
- LSTM model provides better performance for sequential predictions  

---

## 📊 Model Performance
- Linear Regression: Baseline predictive accuracy using regression metrics  
- LSTM Model:  
  - Mean Absolute Error (MAE): ~69.52  
  - Improved trend-following capability over traditional models  
