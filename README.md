HOUSE SALES ANALYSIS

Overview

This project analyses the sale prices of different properties in Washington county using a dataset downloaded from Kaggle but sourced from the book "Practical Statistics for Data Scientists" by Peter Bruce, Andrew Bruce, and Peter Gedeck.

Research Questions:

How, on average, costed a Single Family, Townhouse, Multiplex in King County area, USA, in 2006?
How did the average prices of the latter change over the 9 years period (2006 - 2015)?
Was the cost of the different properties associated with their respective living area sizes in 2006?

Analysis

Tools and Technologies:

Python 
Jupyter Notebook
pandas
matplotlib
SciPy

The project includes:

Data inspection 
Missing-value analysis
Checking and removing some duplicate observations irrelevant to the analysis
Average sale prices for each property type in 2006
Line graphs to see the change in sale prices overtime 
Scatter plots to see if there was a an association between sale prices and property size in 2006 for the three properties
Simple linear regression on the interested variables (sale prices and total living area) on each property type in 2006

Main Findings:

"Single Family" properties were more expensive than "Townhouse" and "Multiplex" properties in 2006. "Townhouse" properties were the cheapest of the three.

Troughout the nine years period, the sale prices have fluctuated for all property types. Overall, the sale prices for "Multiplex" have increased but decreased for "Single Family" and "Townhouse" properties.

For the three property types, there was a statistically significant linear relationship between the total living area and the sale price in 2006 with the unequal variance (violated simple linear regression assumption) as a limitation of the analysis.

Project Structure:

CSV: house_sales.csv
Jupyter Notebook: house_prices analysis.ipynb
README.md — project documentation

How to Run:

Clone the repository.
Make sure Python and the required libraries are installed.
Place the CSV dataset in the same directory as the Jupyter Notebook.
Open the notebook and run the cells from top to bottom.


This project documents my progress in learning data analysis using python.


