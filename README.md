# Stock Market Analysis Using Big Data Technologies

## Overview

This project focuses on analyzing stock market data using Big Data technologies, machine learning, and sentiment analysis to generate meaningful insights and support decision-making.

Stock market prediction is a complex task influenced by multiple factors such as economic indicators, company performance, global events, and investor sentiment. This system combines structured financial data with unstructured social media data to provide a more comprehensive understanding of market behaviour. 

---

## Abstract

The project leverages large-scale datasets and advanced analytical tools to analyze stock market trends. Traditional methods rely mainly on historical numerical data and fail to capture psychological and emotional factors influencing stock prices.

To address this limitation, the system integrates sentiment analysis using Natural Language Processing (NLP) techniques to classify public opinion into positive, negative, or neutral categories.

By combining historical stock data with real-time sentiment data, the system enhances prediction accuracy and provides a holistic view of market trends. 

---

## Problem Statement

Traditional stock analysis systems have two major limitations:

* Dependence only on historical numerical data
* Inability to process large-scale structured and unstructured data efficiently

This leads to incomplete analysis and inaccurate predictions. 

---

## Objectives

* Perform large-scale data aggregation using Big Data technologies
* Analyze historical stock market data
* Apply sentiment analysis on social media and news data
* Build machine learning models for prediction
* Visualize trends and insights for better decision-making
* Combine quantitative and qualitative analysis for improved accuracy 

---

## Technologies Used

### Programming Language

* Python

### Libraries and Tools

* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* yfinance
* NLTK / TextBlob

### Big Data & Storage

* CSV / JSON datasets
* Optional: MongoDB or PostgreSQL

### Development Tools

* Jupyter Notebook
* VS Code

---

## System Architecture

Data Sources → Data Collection → Data Preprocessing → Feature Engineering → Machine Learning Model → Sentiment Analysis → Visualization → Decision Support

---

## Dataset Description

The dataset consists of historical stock market data collected from APIs such as yfinance.

Attributes include:

* Date
* Open Price
* Close Price
* High Price
* Low Price
* Volume
* Adjusted Close

Derived features:

* Moving Averages (SMA, EMA)
* RSI (Relative Strength Index)
* Daily Returns
* Volatility Measures 

---

## Methodology

### 1. Data Collection

Stock data is collected using APIs such as yfinance and social media data is gathered for sentiment analysis.

### 2. Data Preprocessing

* Handling missing values
* Removing duplicates
* Data normalization
* Formatting time-series data

### 3. Feature Engineering

* Technical indicators (SMA, EMA, RSI)
* Volatility and trend features

### 4. Machine Learning

* Random Forest Classifier
* Linear Regression (for prediction)

Prediction Output:

* 1 → Price Increase
* 0 → Price Decrease 

### 5. Sentiment Analysis

* NLP techniques used to classify sentiment
* Categories: Positive, Negative, Neutral

### 6. Risk Evaluation

* Volatility-based scoring
* Trend confirmation techniques

### 7. Visualization

* Price trend graphs
* Indicator plots
* Prediction vs actual comparison

---

## Features

* Stock trend analysis
* Sentiment-based prediction
* Risk evaluation system
* Machine learning-based forecasting
* Interactive visualization and dashboards

---

## Implementation

The system is implemented using Python with data analytics and machine learning libraries.

The workflow includes:

* Data ingestion and preprocessing
* Feature extraction
* Model training and prediction
* Visualization using charts and dashboards

An interactive dashboard (Streamlit) is used to display:

* Stock trends (Bullish / Bearish)
* Risk levels (Low / Medium / High)
* Predictions and confidence scores
* Buy / Hold / Avoid suggestions 

---

## Results

The system successfully:

* Identifies stock market trends
* Predicts price movements
* Evaluates risk levels
* Provides visual insights

Graphs (as shown in the documentation) include:

* Stock price prediction vs actual values (page 18)
* Multi-stock trend comparison (page 19) 

---

## Challenges

* Noise in social media data (slang, sarcasm, multilingual text)
* Data preprocessing complexity
* Ensuring data privacy and ethical usage

---

## Conclusion

This project demonstrates the effectiveness of combining Big Data technologies, machine learning, and sentiment analysis for stock market prediction.

By integrating both quantitative (historical data) and qualitative (sentiment data) analysis, the system provides more accurate and reliable insights compared to traditional methods. 

---

## Future Scope

* Deep learning models (LSTM, Transformers)
* Real-time data streaming (Kafka)
* Multilingual sentiment analysis
* Cloud deployment
* Advanced decision-support systems 

---

## Authors

* Uday Raman Senthil Kumar
* Veera Balaji Naidu Vaddi

---
