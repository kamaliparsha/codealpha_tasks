# Task 1 — Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Online Retail dataset using Python. The objective is to understand retail transaction patterns, identify sales trends, analyze product performance, and explore customer purchasing behavior.

This project was completed as part of the **CodeAlpha Data Analytics Internship — October Batch**.

## Dataset

- **Dataset:** Online Retail Dataset
- **Source:** [UCI Machine Learning Repository — Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Original Records:** 541,909
- **Original Features:** 8

The dataset contains online retail transactions, including invoice numbers, product descriptions, quantities, invoice dates, unit prices, customer IDs, and countries.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning and Preprocessing

The following preprocessing operations were performed:

1. Loaded the Online Retail Excel dataset using Pandas.
2. Identified and removed duplicate records.
3. Removed rows with missing values in essential transaction fields.
4. Excluded cancelled invoices.
5. Removed transactions with non-positive quantities or unit prices.
6. Created a new `Revenue` column using:

   `Revenue = Quantity × UnitPrice`

7. Prepared the cleaned dataset for further analysis.

Missing CustomerID values were retained where possible because customer identification was not essential for overall sales analysis.

## Exploratory Data Analysis

The analysis includes:

- Dataset structure and summary statistics.
- Missing-value and duplicate analysis.
- Country-wise sales analysis.
- Product-wise revenue analysis.
- Monthly revenue trends.
- Daily revenue distribution.
- Identification of top-performing products and countries.

## Key Findings

- The original dataset contains 541,909 transaction records.
- After cleaning, 524,878 records remained.
- The total revenue of the cleaned dataset was approximately **£10.64 million**.
- The United Kingdom generated the highest revenue.
- DOTCOM POSTAGE was the highest-revenue product description in the analysis.
- Monthly revenue analysis showed changes in sales throughout the year, with November recording a particularly strong sales month.

*Note: December 2011 contains only partial-month data in the dataset.*

## Visualizations

The project includes the following visualizations:

1. Monthly Retail Revenue Trend
2. Top 10 Products by Revenue
3. Top 10 Countries by Revenue
4. Distribution of Daily Retail Revenue

## Project Files

| File | Description |
|---|---|
| `01_retail_eda.ipynb` | Complete Python notebook containing data cleaning, EDA, analysis, and visualizations |
| `README.md` | Project documentation |

## How to Run the Project

1. Open the notebook `01_retail_eda.ipynb`.
2. Open it in Google Colab or Jupyter Notebook.
3. Download the Online Retail dataset from the UCI Machine Learning Repository.
4. Upload the Excel dataset when prompted by the notebook.
5. Run all cells sequentially to reproduce
