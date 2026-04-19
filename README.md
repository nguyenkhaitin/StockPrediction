# Stock Price Prediction & Statistical Analysis

[Streamlit App Demo](https://stockprediction-nktin.streamlit.app)

<img width="1920" height="910" alt="image" src="https://github.com/user-attachments/assets/7e983e3e-9ab2-4a82-9571-056b2fe5fb27" />


> *An interactive web application for stock price forecasting using time-series statistical models.*

This project was developed by **Team 11** for the **Data Analysis for Management** course at the **University of Social Sciences and Humanities (USSH)**. It leverages statistical methods and machine learning concepts to analyze historical stock data and predict future price trends, aiding investors in making data-driven decisions.

---

### My Role: Data Analyst & Product Lead
In this project, I managed the end-to-end data product lifecycle, focusing on transforming raw stock data into actionable investment insights:

* **ETL & Data Cleaning:** Orchestrated the data pipeline by extracting raw CSV files and using **Power Query** to clean, transform, and handle anomalies (Z-Score analysis).
* **Statistical Logic & Analysis:** Formulated key business questions to extract meaningful outputs (Returns, Volatility, Correlation). I built a **Dynamic Excel Dashboard** to compare Fashion sector tickers (NKE, ADDYY, VFC) with interactive filters.
* **Tech Transformation:** Translated static Excel models and charts into a scalable **Python** environment, leveraging **Streamlit** to build a real-time web interface.
* **Forecasting Implementation:** Directly implemented time-series algorithms (Holt-Winters, MA, etc.) into the web app, allowing users to run predictive models on pre-loaded datasets.


---

### Key Objectives
* **Predictive Modeling:** Develop and evaluate accurate forecasting models using statistical time-series analysis.
* **Sector Analysis:** Compare model performance across diverse industries with varying volatilities.
* **Interactive Visualization:** Build a user-friendly, real-time dashboard for investors.

---

### Dataset & Scope
Data is extracted from **Yahoo Finance**, focusing on historical adjusted closing prices, trading volumes, and return metrics for 5 major corporations across 3 distinct sectors:
* **Fashion:** NIKE (NKE), ADIDAS (ADDYY), VF Corporation (VFC)
* **Engineering / Automotive:** TESLA (TSLA)
* **Technology:** NOKIA (NOK)

---

### Two-Pillar Analytical Approach
This project is strategically divided into two core phases: diagnosing historical data and forecasting future trends.

#### Phase 1: Data Analysis & Business Intelligence
Before applying predictive algorithms, I established a foundation of statistical logic to understand market behaviors and volatility:
* **Exploratory Data Analysis (EDA):** Conducted Hypothesis testing (Run test) for randomness, Z-Score for anomaly detection, and return volatility tracking.
* **Interactive Dashboarding:** Built a dynamic Business Intelligence Dashboard to cross-compare the Fashion sector (NIKE, ADIDAS, VFC) using custom timeframes and statistical filters.

<img width="1745" height="667" alt="image" src="https://github.com/user-attachments/assets/3c5d826c-61e3-445b-9685-2de4d9df1e5d" />

#### Phase 2: Time-Series Forecasting Models
Leveraging the cleaned data pipelines, I implemented advanced statistical algorithms in Python to predict future stock price movements:
* **Baseline Models:** Moving Average (MA) & Weighted Moving Average (WMA).
* **Advanced Smoothing:** Exponential Smoothing (ES).
* **Trend & Seasonality:** Holt’s Linear Trend Model (Double ES) and Holt-Winters Model (Triple ES) to capture complex market cycles.

<img width="1920" height="919" alt="image" src="https://github.com/user-attachments/assets/925b0ae7-0b30-4cdf-8186-1be06272cca5" />

---

### Technical Stack
* **Language:** Python
* **Data Processing & Math:** Pandas, NumPy, SciPy, Statsmodels
* **Data Visualization:** Microsoft Excel, Matplotlib, Seaborn
* **Web Framework:** Streamlit
* **ETL Tools:** Power Query, Microsoft Excel
