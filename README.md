# connectate-analysis
# ConnectaTel Telecommunications Analysis

## Project Objective

This project analyzes customer mobile usage for ConnectaTel, a telecommunications company operating in Mexico and Colombia.

The objective is to identify usage patterns, detect outliers and unusual behaviors, and segment customers based on age and service usage in order to support commercial decisions and improve the customer experience.

## Datasets Used

The analysis uses three datasets:

- `plans.csv`: information about available plans, prices, included benefits, and extra usage costs.
- `users_latam.csv`: customer information such as age, city, registration date, and contracted plan.
- `usage.csv`: customer activity, including calls, call duration, messages, and message length.

## Analysis Stages

The project includes the following stages:

1. Data loading and initial exploration.
2. Missing value analysis.
3. Detection and correction of sentinel values.
4. Date validation and standardization.
5. Descriptive statistical analysis.
6. Aggregation of usage by customer.
7. Visualization of distributions.
8. Outlier detection using boxplots and the IQR method.
9. Customer segmentation by age.
10. Customer segmentation by usage level.
11. Executive insights and business recommendations.

## Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook
- Google Colab

## How to Run the Notebook

1. Open the notebook in Google Colab.
2. Upload the following datasets:
   - `plans.csv`
   - `users_latam.csv`
   - `usage.csv`
3. Make sure the file paths point to `/content/`.
4. Run the notebook cells in order.

The main notebook is located at:

`notebooks/connectatel_analysis.ipynb`

## Reproduction Guide

To reproduce the analysis:

1. Download or clone this repository.
2. Open `connectatel_analysis.ipynb` in Google Colab.
3. Upload the required CSV files.
4. Execute all cells from top to bottom.
5. Review the generated tables, visualizations, segmentation results, and business conclusions.

## Main Objective for the Business

The analysis helps ConnectaTel understand how different groups of customers use calls and messages, identify unusual usage patterns, and detect opportunities to improve existing plans or create more suitable offers for different customer segments.
