# Exploratory Data Analysis – House Prices

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Ames Housing Dataset to understand house price distributions, identify patterns, detect outliers, and explore relationships between different housing features.

The analysis is performed using Python and its data analysis and visualization libraries.

## Dataset
- **Dataset:** Ames Housing Dataset
- **File:** `train.csv`
- **Records:** 1,460 rows
- **Features:** 81 columns
- **Source:** [Kaggle – House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Project Objectives
- Understand the structure and characteristics of the dataset.
- Identify and handle missing values.
- Detect duplicate records.
- Analyze numerical and categorical features.
- Calculate descriptive statistics.
- Study data distributions and skewness.
- Apply log transformation to SalePrice.
- Identify potential outliers.
- Explore relationships and correlations between housing features.
- Visualize important patterns in house prices.

## Analysis Performed

### 1. Data Inspection
- Dataset shape and structure
- Column information and data types
- Unique values in categorical columns

### 2. Data Cleaning
- Missing value analysis
- Duplicate record detection
- Categorical value cleaning
- Missing LotFrontage values handled using neighborhood-wise median imputation

### 3. Descriptive Statistics
- Mean, median, and mode
- Standard deviation and variance
- Range and interquartile range
- Skewness and kurtosis

### 4. Data Visualization
- Histograms
- Boxplots
- Scatter plots
- Correlation analysis
- Log-transformed SalePrice distribution

### 5. Outlier Analysis
- Interquartile Range (IQR) method
- Z-score method
- Identification of unusual housing observations

## Key Findings
- House prices generally show a right-skewed distribution.
- Log transformation helps reduce the skewness of SalePrice.
- OverallQual and GrLivArea show strong positive relationships with SalePrice.
- House prices vary across different neighborhoods.
- Some unusually large or expensive houses may be potential outliers.
- Missing values in certain categorical features can represent the absence of that feature.

## Conclusion
This project provides an understanding of the Ames Housing Dataset through statistical analysis and data visualization. It highlights important patterns and relationships between housing features and sale prices without using machine learning models