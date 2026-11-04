# Personal Finance Analytics Using Python
Analysis of UPI transactions for 2023–2024 using Python. The project explores spending patterns, income/deposit trends, category-wise expenses, and monthly savings through interactive-style data analysis and visualizations.

## Project Overview
This notebook analyzes a personal transaction dataset containing 1,470 records with columns for transaction date, category, reference number, withdrawal, deposit, and balance. It identifies where money was spent, how deposits varied by month, and whether monthly income exceeded expenses.

## Dataset
= File: MyTransaction.xlsx

= Period: 2023–2024

= Records: 1,470 transactions

= Columns: Date, Category, RefNo, Withdrawal, Deposit, Balance, year, month

= Expense categories: Misc, Food, Rent, Shopping, Transport, and Salary

## Technologies Used
- Python 3

- pandas — data loading, cleaning, and aggregation

- matplotlib — bar charts, line charts, and pie charts

- seaborn — category/month spending heatmap

- Google Colab — notebook execution and Excel file upload

## Analysis Performed
= Loaded and inspected the UPI transaction dataset

- Calculated total withdrawals and deposits by year and month

- Analyzed category-wise spending distribution

- Examined monthly Food and Miscellaneous expenses

- Compared deposits and withdrawals from January to April 2023

- Calculated monthly savings as Deposit - Withdrawal

- Visualized spending trends, savings trends, and category heatmaps

## Key Visualizations
= Category-wise spending pie chart

= Monthly Food spending bar chart

= Withdrawal trend from May to August 2023

= Deposit analysis for January–April 2023

= Deposit vs. withdrawal comparison chart

= Monthly savings bar and trend charts

= Category spending heatmap by month

## How to Run
= Open personal_finance_analytics_using_python.ipynb in Google Colab or Jupyter Notebook.

= Install the required libraries if needed:

= bash
pip install pandas matplotlib seaborn openpyxl

= Upload MyTransaction.xlsx when prompted, or place it in the same directory as the notebook.

= Run all notebook cells to generate the analysis and charts.

## Sample Insights
= Miscellaneous expenses were the largest spending category, followed by Food and Rent.

= Total 2023 deposits were ₹565,920.25.

= Monthly savings were positive in January, February, and March 2023, but negative in April 2023.

= The notebook includes visual dashboards for spending, deposits, withdrawals, and savings.Monthly savings were positive in January,

## Future Improvements
= Add automated data-cleaning functions

= Include a forecasting model for future expenses and savings

= Build an interactive dashboard using Plotly Dash or Streamlit

= Add budget limits and overspending alerts by category
February, and March 2023, but negative in April 2023.

The notebook includes visual dashboards for spending, deposits, withdrawals, and savings.
