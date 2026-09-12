# Seasonal Agriculture Performance Analysis

## VOIS AICTE Batch 1 — Major Project

### Project Overview

This project analyzes agricultural data across different seasons to identify meaningful patterns, trends, relationships, differences and variations in agricultural performance.

The analysis focuses on **Kharif, Rabi and Zaid** seasons and examines agricultural, environmental, resource and economic variables.

## Problem Statement

Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability and market conditions. As a result, agricultural performance may differ from one season to another.

The project investigates seasonal differences in agricultural performance using data analysis and visualization.

## Objectives

- Explore and understand the dataset.
- Clean and prepare the data.
- Examine agricultural performance across seasons.
- Identify seasonal patterns and trends.
- Investigate relationships between seasonal conditions and agricultural outcomes.
- Compare relevant groups across seasons.
- Identify significant differences and unusual patterns.
- Apply statistical and visualization techniques.
- Interpret findings based on evidence.
- Develop data-driven conclusions and recommendations.

## Dataset

The dataset contains **4,000 farm records and 28 variables** covering:

- State and district
- Crop and season
- Farm area
- Yield and production
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil properties
- Nutrient inputs
- Irrigation method
- Fertilizer and pesticide usage
- Seed quality
- Market price
- Cost
- Revenue
- Profit
- Water use
- Water efficiency
- Disease/pest risk

### Seasons

- Kharif
- Rabi
- Zaid

## Research Questions

1. How does crop yield vary across Kharif, Rabi and Zaid?
2. How does agricultural profitability vary across seasons?
3. How do environmental conditions vary across seasons?
4. What relationships exist between environmental conditions and crop yield?
5. How does irrigation method relate to water use and agricultural performance?
6. How does crop choice relate to yield and profitability?
7. Do agricultural outcomes differ significantly between seasons?
8. Are seasonal patterns consistent across states and crops?

## Methodology

```text
Raw Dataset
    ↓
Data Understanding
    ↓
Data Cleaning
    ↓
Exploratory Data Analysis
    ↓
Seasonal Comparison
    ↓
Crop & Irrigation Analysis
    ↓
Environmental Analysis
    ↓
Economic Analysis
    ↓
Correlation Analysis
    ↓
Statistical Testing
    ↓
Findings & Recommendations
```

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

## Key Findings

The supplied dataset shows clear descriptive differences among seasons.

- Kharif has the highest average profit in the dataset.
- Zaid has the lowest average profit and a negative average profit in the supplied data.
- Disease/pest risk is highest on average in Kharif.
- Crop yields vary substantially by crop and season.
- Sugarcane has a much larger numerical yield scale than the other crops, so crop comparisons must consider crop type and measurement scale.
- Irrigation methods show differences in average yield, profit and water use.

### Statistical analysis

For seasonal yield, the project uses both non-parametric and parametric tests:

- Kruskal–Wallis: **H = 68.60, p < 0.001**
- One-way ANOVA: **F = 1.46, p = 0.233**

These results demonstrate why distribution shape and crop composition should be considered when interpreting seasonal yield differences.

## Important Analytical Limitations

This project does **not** claim that season, irrigation or environmental variables independently cause observed outcomes.

Important considerations include:

1. The dataset is observational.
2. Crop composition can influence aggregate seasonal averages.
3. Production, revenue and profit are mathematically related variables.
4. Water efficiency is derived from production/yield and water use.
5. Yield is strongly skewed because some crops have much larger numerical yield values.
6. The dataset does not provide a multi-year time series for long-term trend analysis.

## Repository Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── data/
│   └── seasonal_agriculture_performance_dataset.csv
│
├── cleaned_data/
│   └── seasonal_agriculture_cleaned.csv
│
├── charts/
│   ├── ppt_seasonal_yield.png
│   ├── ppt_seasonal_profit.png
│   ├── ppt_rainfall.png
│   ├── ppt_environment.png
│   ├── ppt_crop_yield.png
│   ├── ppt_irrigation_water.png
│   ├── ppt_irrigation_yield.png
│   └── ppt_correlation.png
│
├── presentation/
│   └── VOIS_Seasonal_Agriculture_Performance_Analysis_FINAL.pptx
│
└── screenshots/
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Seasonal-Agriculture-Performance-Analysis.git
cd Seasonal-Agriculture-Performance-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Seasonal_Agriculture_Performance_Analysis.ipynb
```

### 4. Run the notebook

Run the cells sequentially to reproduce the analysis and visualizations.

## Project Deliverables

- Jupyter Notebook
- Original dataset
- Cleaned dataset
- Analysis charts
- Final VOIS presentation

## Author

**Anurag Shah**

B.Tech — Textile Technology

College: **[Your College Name]**

AICTE STU ID: **[Your STU ID]**

## Submission

This repository supports the VOIS Major Project submission for:

**Seasonal Agriculture Performance Analysis**
