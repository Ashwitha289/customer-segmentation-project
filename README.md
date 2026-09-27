# Customer Segmentation Project

## Project Overview

This project performs customer segmentation using K-Means clustering based on customer income and total spending.

## Objectives

- Segment customers into meaningful groups.
- Analyze customer income and spending patterns.
- Determine the appropriate number of clusters using the Elbow Method.
- Evaluate clustering using the Silhouette Score.
- Visualize the customer segments.
- Identify unusual observations and check for missing values.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

The analysis uses customer demographic and spending data stored in `customer_segmentation.csv`.

## Methodology

K-Means clustering was applied using:

- Income
- Total Spending

The Elbow Method and Silhouette Score were used to evaluate the clustering.

## Results

The analysis identified three customer clusters with different income and spending characteristics.

An unusually high income value of 666,666 was identified and retained as an outlier for investigation.

No missing values were found in the Income and Total_Spending variables.

## Files

- `customer_segmentation.ipynb` — Complete analysis and visualizations.
- `customer_segmentation.csv` — Dataset used for the analysis.
