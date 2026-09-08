# Seasonal Agriculture Performance Analysis

This is a data analytics project done as part of my VOIS AICTE internship. The goal of this 
project is to analyze a seasonal agriculture dataset and understand how farming performance 
changes across different seasons (Kharif, Rabi, Zaid) in India.

## Problem Statement
Agricultural performance is affected by seasonal changes in weather, farming practices and 
resource availability. But just by looking at raw data, it's not clear how performance actually 
changes from one season to another. This project analyzes the dataset to find seasonal patterns, 
trends and differences in agricultural performance.

## About the Dataset
The dataset has around 4000 records and 28 columns, covering:
- 3 seasons: Kharif, Rabi, Zaid
- 8 states
- 8 crops
- 4 irrigation methods

It includes information about weather conditions (rainfall, temperature, humidity), soil, 
fertilizer and water usage, and economic outcomes like cost, revenue and profit.

## What I Did
- Cleaned the data (checked missing values, filled them using mean/group-mean, checked duplicates)
- Did statistical analysis (mean, median, standard deviation, skewness, kurtosis)
- Did univariate analysis on all numeric and categorical columns (histograms, boxplots, 
  violin plots, pie charts)
- Did bivariate analysis (scatter plots, bar plots, crosstab heatmap, correlation with yield)
- Did multivariate analysis (correlation heatmap, FacetGrid, pairplot, state-season heatmap)
- Did outlier analysis using the IQR method
- Wrote interpretations after each chart based on what the data actually showed
- Wrote final conclusions, recommendations and limitations

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

## Files in this Repository
- `Seasonal_agriculture_performance_Analysis.ipynb` - main notebook with the full analysis
- `seasonal_agriculture_performance_dataset.csv` - dataset used for this project

## Key Findings
- Kharif season has the highest average yield and profit, while Zaid season shows a loss 
  on average
- Disease/pest risk is higher in Kharif season, likely due to more humidity and rainfall
- Drip irrigation gives better average yield compared to other irrigation methods
- Cash crops like Sugarcane and Chilli are more profitable than staple crops like Rice, 
  Wheat and Maize
- Yield is most correlated with water efficiency and production, not any single factor 
  like rainfall alone
- Columns like Yield, Profit, Production and Water Efficiency have a good number of outliers, 
  which could be high-performing farms

## How to Run
1. Clone this repository
2. Open `Seasonal_agriculture_performance_Analysis.ipynb` in Jupyter Notebook or Google Colab
3. Make sure `seasonal_agriculture_performance_dataset.csv` is in the same folder / uploaded
4. Run all cells from top to bottom

## Author
DEEPIKA E  
GRT Institute of Engineering and Technology  
VOIS AICTE Internship Batch 2026-2027
