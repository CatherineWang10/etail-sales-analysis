# retail-sales-analysis
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

- `Retail and wherehouse Sale.csv`

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
- `Untitled.ipynb`
- `Retail and wherehouse Sale.csv`

## How to Run
1. Download the project files.
2. Make sure `Retail and wherehouse Sale.csv` is in the same folder as the notebook.
3. Install the required Python libraries:
   - pandas
   - matplotlib
   - seaborn
4. Open the notebook in Jupyter Notebook.
5. Run the cells in order from top to bottom.

## Example Data Loading Code
```python
import pandas as pd

df = pd.read_csv("Retail and wherehouse Sale.csv")
我看到了，你这个问题很明确：

## 原因
你把 `## Conclusion` **粘贴到了代码块里面**。

因为你上面有这一行：

```md
```python
```

但是你**没有先用三个反引号把代码块结束掉**，所以 GitHub 认为下面所有内容都还是 Python 代码，包括：

- `## Conclusion`
- 后面的段落文字

所以看起来就像“编码”。

---

# 你现在怎么改
你需要在这行代码后面：

```md
df = pd.read_csv("Retail and wherehouse Sale.csv")
```

**马上加一行：**

```md
```
```

也就是再输入 **三个反引号**，把代码块关掉。

---

# 正确写法应该是这样
你把这一整段改成下面这样就对了：

```md
## Example Data Loading Code
```python
import pandas as pd

df = pd.read_csv("Retail and wherehouse Sale.csv")
```

## Conclusion
This project demonstrates a small but coherent Python-based data analysis product in a business context.  
Using retail sales data, the notebook applies data inspection, preparation, descriptive analysis, and visualisation to generate interpretable insights for a defined user audience.

The analysis helps identify sales patterns, compare performance across suppliers and item types, and observe monthly trends over time.  
Overall, the project shows how Python can be used to support business understanding and communicate useful analytical insights clearly.
```

---

# 你这个截图里还要顺手改一个小问题
你现在有 **两个 `## Conclusion`**：

一个在代码块里面：

```md
## Conclusion
```

一个在下面正文里：

```md
## Conclusion
```

## 正确做法：
**删掉前面那个多余的 `## Conclusion`**，只保留后面一个。

---

# 最终你这一部分应该长这样

直接照着改：

```md
## Example Data Loading Code
```python
import pandas as pd

df = pd.read_csv("Retail and wherehouse Sale.csv")
```

## Conclusion
This project demonstrates a small but coherent Python-based data analysis product in a business context.  
Using retail sales data, the notebook applies data inspection, preparation, descriptive analysis, and visualisation to generate interpretable insights for a defined user audience.

The analysis helps identify sales patterns, compare performance across suppliers and item types, and observe monthly trends over time.  
Overall, the project shows how Python can be used to support business understanding and communicate useful analytical insights clearly.
```

