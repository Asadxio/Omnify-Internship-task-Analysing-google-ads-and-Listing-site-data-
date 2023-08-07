# Omnify-Internship-task-Analysing-google-ads-and-Listing-site-data-

# Omnify Final - Jupyter Notebook

This Jupyter Notebook contains the analysis of ad campaign data for Omnify. The notebook includes several steps to import the necessary libraries, load the dataset, clean the data, visualize the distribution of key metrics, perform cohort analysis, and find the most profitable channel and category/keyword.

## Step 1: Import necessary libraries and load the dataset
The initial step is to import the required Python libraries, such as pandas, matplotlib, and seaborn, and then load the dataset using pandas' `read_excel` function.

## Step 2: Check the first few rows of the dataset and get an overview of the dataset
This step displays the first few rows of the dataset to get an overview of the data structure.

## Step 3: Data Visualization - Distribution of 'Cost ($)', 'Impressions', 'Clicks', and 'Prospects'
In this step, histograms are created to visualize the distribution of 'Cost ($)', 'Impressions', 'Clicks', and 'Prospects' in the dataset.

## Step 4: Data Cleaning - Convert 'Payment ($)' columns to float, calculate 'Returns %'
This step involves data cleaning by converting the 'Payment ($)' and 'Cost ($)' columns to float data type. Additionally, the 'Returns %' column is calculated by dividing 'Payment ($)' by 'Cost ($)' and multiplying by 100.

## Step 5: Cohort Analysis - Average Returns % over time
Cohort analysis is performed to calculate the average 'Returns %' over time, visualized using a line plot.

## Step 6: Key Metrics in Weekly and Monthly Format
The key metrics, including 'Cost ($)' and 'Returns %,' are aggregated on a weekly and monthly basis.

## Step 7: Find the most profitable channel and category/keyword
The most profitable channel and category/keyword are identified based on the calculated 'Returns %' values.

## Step 8: Time Series Graphs - Spends and Returns % over time
Time series graphs are generated to visualize the trends in 'Spends' and 'Returns %' over time.

Please note that this README file is auto-generated from a Jupyter Notebook, and the results might vary based on the dataset used during the analysis.
