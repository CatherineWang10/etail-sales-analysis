# etail-sales-analysis
# Retail Sales Analysis

## Project Overview
This project presents a small Python-based data analysis product using a retail sales dataset.  
The aim is to explore sales patterns, compare performance across product categories and suppliers, and identify monthly sales trends over time.

The project was developed in Jupyter Notebook and includes data cleaning, descriptive analysis, and visualisation to communicate useful business insights.

## Analytical Problem
The analytical problem addressed in this project is:

**How can retail sales data be used to identify sales patterns, compare category performance, and understand how sales change over time?**

This problem is relevant to a business context because retail managers and analysts often need to understand which products perform better, whether some suppliers contribute differently to sales outcomes, and whether sales vary across months.

## Target User / Audience
The intended audience for this project includes:

- beginner business analysts
- retail decision-makers
- marketing or operations students
- users who want a simple overview of retail sales behaviour

The product is designed to communicate analytical value clearly through charts and summary findings rather than only presenting raw code.

## Dataset
The dataset used in this project is:

- `retail and wherehouse sale.csv`

The dataset contains retail-related variables such as:

- `YEAR`
- `MONTH`
- `SUPPLIER`
- `ITEM CODE`
- `ITEM DESCRIPTION`
- `ITEM TYPE`
- `RETAIL SALES`
- `RETAIL TRANSFERS`
- `WAREHOUSE SALES`

These variables allow analysis of sales distribution, comparisons across item types and suppliers, and monthly trend analysis.

## Dataset Source
The dataset was obtained from Kaggle.

**Source:** Retail Sales Data with Seasonal Trends & Marketing  
**Platform:** Kaggle  
**Accessed on:** 9 April 2026

## Business Relevance
Retail sales analysis is important in business because it helps organisations:

- understand sales performance
- compare different product groups
- identify variation across suppliers
- observe trends over time
- support decision-making in marketing, inventory, and operations

This makes the dataset suitable for a business-related Python analysis assignment.

## Python Workflow
The notebook follows a clear analytical workflow from data input to final output.

### 1. Data Loading
The dataset is loaded into Python using pandas.

### 2. Data Inspection
Initial exploration is carried out using:

- `df.head()`
- `df.info()`
- `df.describe()`
- `df.isnull().sum()`

These steps help understand the structure of the dataset, identify variable types, and check for missing values.

### 3. Data Preparation
Basic preparation includes:

- checking the quality of the data
- creating a date column from `YEAR` and `MONTH`
- preparing variables for grouping and visualisation

### 4. Data Analysis
Python is used to perform descriptive analysis of retail sales, including:

- sales distribution analysis
- comparison by supplier
- comparison by item type
- monthly aggregation of sales

### 5. Data Visualisation
The project uses matplotlib and seaborn to present findings clearly through charts.

## Visualisations and Findings

### 1. Retail Sales Distribution
A histogram with KDE is used to show the distribution of retail sales values.  
This helps identify the spread of the data and whether sales values are concentrated in certain ranges.

### 2. Retail Sales by Supplier
A boxplot is used to compare retail sales across different suppliers.  
This helps reveal differences in distribution, median sales levels, and possible outliers.

### 3. Retail Sales by Item Type
A boxplot is used to compare sales across item types.  
This makes it easier to identify which categories show higher or lower sales variation.

### 4. Monthly Retail Sales Over Time
A date variable is created from the year and month columns, and retail sales are aggregated by month.  
A line chart is then used to visualise monthly retail sales trends over time.

## Key Insights
The analysis shows that:

- retail sales are not evenly distributed
- sales patterns differ across suppliers
- item types show different sales behaviour
- monthly sales change over time, suggesting trend or seasonal variation

These findings provide a simple but useful business-focused view of the dataset.

## Tools and Technologies
This project was completed using:

- Python
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

## Project Files
The project includes the following files:

- `README.md`
- `untitled.ipynb`
- `retail and wherehouse sale.csv`

## How to Run
1. Download the project files.
2. Make sure `retail and wherehouse sale.csv` is in the same folder as the notebook.
3. Install the required Python libraries:
   - pandas
   - matplotlib
   - seaborn
4. Open the notebook in Jupyter Notebook.
5. Run the cells in order from top to bottom.

## Example Data Loading Code
```python
import pandas as pd

df = pd.read_csv("retail and wherehouse sale.csv")
Conclusion
This project demonstrates a small but coherent Python-based data product in a business context.
Using retail sales data, the notebook applies data inspection, preparation, descriptive analysis, and visualisation to generate interpretable insights for a defined user audience.

The project shows how Python can be used not only to process data, but also to communicate analytical value clearly.

Author
Shiyao Wang
