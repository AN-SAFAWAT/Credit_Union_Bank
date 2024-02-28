# Cross-Selling Strategy Enhancement for XYZ Credit Union

## Project Overview

This project was undertaken by ABC Analytics to assist XYZ, a Latin American credit union company, 
in improving its cross-selling strategies for various banking products, including credit cards, savings accounts,
retirement accounts, and safe deposit boxes. The primary objective was to conduct an in-depth Exploratory Data Analysis (EDA) 
on the provided dataset to uncover insights that could drive more effective cross-selling practices.

## Business Statement

The challenge for XYZ has been the effective cross-selling of banking products. ABC Analytics aims to leverage data analytics to identify opportunities
for enhancing these strategies, thereby increasing customer engagement and product uptake.

## Data Understanding

The dataset provided by XYZ includes:

- **File Type**: CSV
- **Size**: 257 MB
- **Observations**: More than 13 million
- **Customers**: Nearly 937k
- **Attributes**: Comprehensive coverage necessary for EDA, including customer demographics, transaction history, and product usage data.

### Data Challenges

- **Data Quality**: Some attributes have incorrect data types that require correction.
- **Missing Values**: The dataset contains missing values, with specific columns having more than 99% null values,
  deemed unnecessary for the analysis.
- **Outliers**: Identified and removed to prevent skewed analysis.

### Preprocessing Steps

1. **Data Cleaning**: Renamed columns for clarity, converted data types to appropriate formats, and removed columns with excessive null values.
2. **Handling Missing Values**: Filled missing values in the 'Gross Income' column with the average of existing values.
   Analyzed and filled other missing values based on their impact and proportion in the dataset.
4. **Outlier Removal**: Utilized boxplots and value counts to identify and remove outliers.

## Methodology

- **Exploratory Data Analysis (EDA)**: Conducted using Pandas in Jupyter notebooks, focusing on understanding customer behaviors and identifying patterns
   that could enhance cross-selling opportunities.
- **Visualization**: Created visualizations to better understand customer segments, product preferences, and potential cross-sell opportunities.

## Key Findings and Recommendations
- **Recommendation**: *(Detail on recommendation folder)*
- **final result: Final presentation
  
## Tools Used

- **Data Analysis and Processing**: Pandas, NumPy, Tableau software
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebook

## How to Use This Repository


- `/notebooks`: Jupyter notebooks with all EDA processes and visualization code.
- `/visualizations`: Generated figures and charts from the analysis.
- The visualizations created in Tableau are central to our analysis. They can be accessed through the following links:

- *(https://public.tableau.com/shared/286YB89BW?:display_count=n&:origin=viz_share_link)https://public.tableau.com/shared/286YB89BW?:display_count=n&:origin=viz_share_link*
