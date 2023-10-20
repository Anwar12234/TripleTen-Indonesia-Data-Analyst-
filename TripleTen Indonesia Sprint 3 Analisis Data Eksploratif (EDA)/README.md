# Used Car Sales Analysis

This repository contains an analysis of used car sales data. The dataset comprises information about various aspects of used cars, such as their prices, ages, mileage, conditions, and other relevant features. The goal of this analysis is to gain insights into the factors influencing the prices of used cars and to provide valuable information for potential buyers and sellers.

## Table of Contents
1. [Preprocessing Data](#preprocessing-data)
    - Handling Missing Values
    - Data Cleaning and Transformation
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - Analyzing Core Parameters
    - Handling Outliers
    - Duration of Listings
    - Average Price for Each Vehicle Type
    - Correlation Analysis
3. [Conclusion](#conclusion)

## 1. Preprocessing Data

The initial steps involved in data preprocessing are as follows:

### 1.1. Dataset Overview
- The dataset comprises 51,525 rows and 13 columns, with some columns containing missing values.
- There are no duplicate entries in the dataset.

### 1.2. Handling Missing Values
Missing values in columns such as `model_year`, `cylinders`, `odometer`, `paint_color`, and `is_4wd` were addressed through imputation and transformation.

### 1.3. Data Cleaning and Transformation
Various data quality issues were resolved, including data type conversions and the addition of new columns for analysis.

## 2. Exploratory Data Analysis (EDA)

In this section, we performed an Exploratory Data Analysis to understand the characteristics of the dataset and gather insights:

### 2.1. Analyzing Core Parameters
Parameters like `price`, `car_age`, `avg_mileage`, `condition`, and `cylinders` were analyzed to ensure data accuracy.

### 2.2. Handling Outliers
Outliers were identified and removed from the dataset, resulting in a cleaner and more accurate dataset.

### 2.3. Duration of Listings
The duration of listings was examined, revealing that most listings were removed within 50 days.

### 2.4. Average Price for Each Vehicle Type
The average price of each vehicle type, such as sedan and SUV, was calculated and visualized.

### 2.5. Correlation Analysis
Correlations between various parameters and vehicle prices were investigated.

## 3. Conclusion

In conclusion, this analysis provides valuable insights into the factors affecting used car prices. The dataset was preprocessed to ensure data accuracy, outliers were handled, and an exploratory analysis was conducted. Key findings include the correlation between vehicle age, mileage, condition, and price. This information can be useful for both buyers and sellers in the used car market.

For more detailed information, please refer to the Jupyter Notebook file and the charts included in this repository.
