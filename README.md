# End-to-End Retail Predictive Analytics

This repository presents an end-to-end retail analytics pipeline built on transactional Superstore data.  
The project integrates data preparation, exploratory analysis, time-series forecasting, customer lifetime value (CLV) segmentation, and a recommendation system into a unified predictive analytics workflow.

Primary notebook:
retail_predictive_analytics.ipynb

---

## Project Objectives

- Analyze historical retail sales performance
- Forecast future sales trends
- Identify high-value customers using CLV modeling
- Generate product recommendations using collaborative filtering
- Produce business-ready insights for strategic decision-making

---

## Data Files

This project uses one primary input dataset and generates cleaned and derived outputs.

### 1. Raw Input Data
Superstore with Target Profit WOW2023 W21.csv

Contains:
- Order-level transaction records
- Customer details
- Product categories and sub-categories
- Sales, profit, and target profit metrics

This file serves as the primary data source for all analyses.

---

### 2. Cleaned Dataset
Superstore_Cleaned.csv

- Preprocessed and standardized version of the raw dataset
- Includes cleaned fields and engineered features
- Used for modeling and analytical tasks

---

### 3. Output / Derived Files
high_clv_customers.csv

- Generated from CLV segmentation analysis
- Contains identified high-value customers based on revenue contribution

Additional model outputs (forecasts, recommendations, and visualizations) are generated dynamically within the notebook.

---

## Methodology Overview

### Data Preparation
- Data cleaning and formatting
- Handling missing values
- Feature engineering for customer-level analysis

### Exploratory Data Analysis
- Sales and profit trend analysis
- Category and segment performance
- Profit vs target comparisons
- Customer purchasing behavior insights

### Sales Forecasting
- Model: Prophet (time-series forecasting)
- Captures trend and seasonality
- Generates forward-looking sales projections

### Customer Lifetime Value (CLV)
- Aggregated customer-level metrics
- Revenue-based segmentation
- Identification of high-value customer groups

### Recommendation System
- Technique: Singular Value Decomposition (SVD)
- Collaborative filtering based on customer-product interactions
- Personalized product recommendations

---

## Tech Stack

- Python
- Pandas / NumPy
- Matplotlib / Plotly
- Scikit-learn
- Prophet
- Jupyter Notebook

Dependencies are listed in requirements.txt.

---

## Repository Structure

```
end-to-end-retail-analytics/
│
├── README.md
├── requirements.txt
├── retail_predictive_analytics.ipynb
├── Superstore with Target Profit WOW2023 W21.csv
├── Superstore_Cleaned.csv
├── high_clv_customers.csv
│
└── reports/
    └── Retail_Analytics_Business_Report.pdf
```

---

## How to Run

1. Clone the repository:

git clone https://github.com/<your-username>/end-to-end-retail-analytics.git
cd end-to-end-retail-analytics

2. Install dependencies:

pip install -r requirements.txt

3. Ensure all data files are present in the root directory.

4. Launch Jupyter Notebook and run:

retail_predictive_analytics.ipynb

Run all cells sequentially.

---

## Key Highlights

- Integrated forecasting, segmentation, and recommendation modeling
- Demonstrated practical retail predictive analytics workflow
- Built reproducible, portfolio-ready data science project
- Combined business analysis with machine learning techniques

---

## Author

Zeel Patel  
Data Science | Machine Learning | Data Analytics

---
