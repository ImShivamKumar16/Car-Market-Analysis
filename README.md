# Car Market Trends Analysis with Car Dekho Data

## Project Overview

This project analyzes used-car data from Car Dekho to identify pricing patterns and market trends.

The analysis focuses on factors such as manufacturing year, selling price, present price, kilometres driven, fuel type, seller type, transmission and previous owners.

## Objectives

- Understand the distribution of used-car selling prices.
- Analyze the relationship between present price and selling price.
- Study the effect of car age and kilometres driven on selling price.
- Compare prices across different fuel and transmission types.
- Analyze the relationship between previous owners and selling price.
- Generate useful visualizations and market insights.

## Dataset

The dataset contains 301 records and 9 original columns.

After removing 2 duplicate records, 299 records were used for analysis.

### Main Features

- Car_Name
- Year
- Selling_Price
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Data Analysis

The project includes:

- Data inspection
- Missing-value analysis
- Duplicate-value detection
- Descriptive statistics
- Selling price distribution
- Present price vs selling price analysis
- Kilometres driven vs selling price analysis
- Car age vs selling price analysis
- Fuel type comparison
- Transmission comparison
- Previous owner analysis
- Correlation analysis

## Key Findings

- Present Price has a strong positive relationship with Selling Price.
- The correlation between Present Price and Selling Price is approximately 0.876.
- Car age has a negative relationship with selling price.
- Kilometres driven has a very weak linear relationship with selling price.
- Diesel cars have the highest average selling price among the fuel categories in this dataset.
- Automatic cars have a higher average selling price than manual cars.
- Previous-owner count has a weak relationship with selling price.

## Project Structure

Car-Market-Analysis/

├── Car_Market_Analysis.ipynb

├── 1776311302-P3-Car Market Trends Analysis with Car Dekho Data.csv

├── README.md

└── charts/

    ├── 01_selling_price_distribution.png
    ├── 02_present_vs_selling_price.png
    ├── 03_kms_vs_selling_price.png
    ├── 04_age_vs_selling_price.png
    ├── 05_fuel_type_price.png
    ├── 06_transmission_price.png
    └── 07_correlation_matrix.png

## Conclusion

The analysis shows that several factors are associated with used-car selling prices. Present Price has the strongest numerical relationship with Selling Price in this dataset, while car age generally has a negative relationship with resale value.

The visualizations provide a simple data-driven view of used-car pricing patterns.

## Author

Shivam Kumar
