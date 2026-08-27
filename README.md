# Logistics-Data-Analysis
# E-Commerce Logistics Performance Analysis Using Python

## Project Overview

This project analyzes e-commerce logistics performance using the
Olist Brazilian E-Commerce Public Dataset.

The project focuses on delivery performance, freight costs,
regional delays, predictive analytics, clustering, and route
optimization.

## Objectives

- Analyze logistics performance using KPIs
- Identify delivery delay patterns
- Analyze freight costs and delivery lead time
- Predict delivery performance
- Segment logistics regions using clustering
- Demonstrate route optimization
- Generate data-driven logistics recommendations

## Dataset

The project uses the Olist Brazilian E-Commerce Public Dataset.

Raw dataset files are not included in this repository because of
their size.

Dataset source:

Olist Brazilian E-Commerce Public Dataset

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Key KPIs

- On-Time Delivery Rate
- Delivery Delay Rate
- Average Delivery Lead Time
- Average Freight Cost
- Average Order Value

## Analysis

### Monthly On-Time Delivery

![Monthly OTD](visualizations/01_monthly_otd.png)

### Delivery Delay by State

![Delay by State](visualizations/02_delay_by_state.png)

### Freight vs Delivery Time

![Freight vs Delivery](visualizations/03_freight_vs_delivery_time.png)

### Delivery Time Distribution

![Delivery Distribution](visualizations/04_delivery_time_distribution.png)

### Correlation Analysis

![Correlation Heatmap](visualizations/06_correlation_heatmap.png)

## Machine Learning

A baseline Random Forest regression model was developed to predict
delivery lead time.

Baseline results:

- MAE: 5.86 days
- RMSE: 9.70 days
- R²: 0.059

An improved model will be developed using additional operational
and geographic features.

## Project Structure

```text
Logistics-Data-Analysis/
├── README.md
├── Logistics_Data_Analysis.ipynb
├── data/
├── visualizations/
├── outputs/
├── src/
└── report/
