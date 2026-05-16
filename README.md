# used-car-price--analysis
Analysis and cleaning of a used car pricing dataset
# Used Car Price Analysis & Data Cleaning

## 📌 Project Overview
This project focuses on resolving the **"Information Asymmetry"** in the used car market (often referred to as the 'Lemon Market' in economics). Buyers frequently struggle to understand a vehicle's actual condition and fair market value. 

The objective of this project is to clean a raw dataset of used cars and analyze the primary determinants that influence their resale price, bridging real-world economic theories with data-driven insights.

## 📂 Repository Structure
* **`raw_cars.csv`**: The initial, uncleaned dataset containing missing values, incorrect entries, and anomalies. *(Note: Replace with your actual raw file name)*
* **`clean_cars.csv`**: The finalized, processed dataset after handling missing data, data type corrections, and outlier removal. *(Note: Replace with your actual clean file name)*
* **`clean used car price.ipynb`**: Jupyter Notebook containing the full Python code for data cleaning, Exploratory Data Analysis (EDA), and key insights.
* **`README.md`**: Project documentation (this file).

## 🛠️ Data Cleaning & Processing Steps
The raw data underwent a rigorous cleaning pipeline to ensure reliability for future modeling:
1. **Handling Missing Values:** Identified and treated null values across critical features.
2. **Data Correction:** Fixed incorrect data entries and standardized column formatting.
3. **Outlier Removal:** Filtered out unrealistic anomalies in price, age, and mileage to avoid skewed analysis.

## 📊 Key Findings & Insights
Based on the analysis of the data and supporting research, car prices are not driven by a single factor but a combination of variables:
* **The Age & Mileage Impact:** There is a strong negative relationship. As a vehicle's age and kilometers driven increase, its market price drops significantly.
* **Primary Price Determinants:** 1. Engine Maximum Power
  2. Vehicle Age & Kilometers Driven
  3. Engine Capacity & Brand Reputation
* **Market Complexity:** Recent shortages in new car markets have made used car pricing highly complex, making data cleaning and precise modeling essential.

## 🚀 Tech Stack Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
