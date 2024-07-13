# Python_London_Housing_Data_Analysis
This project analyzes the London housing market using a Kaggle dataset from 1995 to 2019, covering monthly average house prices, yearly house sales, and monthly crime rates. It includes data exploration, preprocessing, and specific queries to reveal housing trends and crime patterns. 

# London Housing Data Analysis

This project involves analyzing the housing market in London using a dataset from Kaggle. The dataset includes monthly average house prices, yearly number of houses sold, and monthly number of crimes committed for various areas in London from 1995 to 2019.

## Dataset

The dataset can be found on Kaggle and contains the following columns:

- **date**: The date of the record
- **area**: The area in London
- **average_price**: The average price of houses in that area
- **code**: The code representing the area
- **houses_sold**: The number of houses sold
- **no_of_crimes**: The number of crimes committed

## Project Overview

The project involves the following steps:

### Data Exploration

Initial exploration of the dataset, including checking for null values and visualizing them using a heatmap.

### Data Preprocessing

- Converting the date column to datetime format.
- Adding new columns for year and month.
- Removing unnecessary columns.

### Data Analysis

Answering specific questions related to the dataset:

- Records where the number of crimes is 0.
- Maximum and minimum average_price per year in England.
- Maximum and minimum number of crimes recorded per area.
- Count of records for each area where the average price is less than 100,000.

## Visualizations

- Heatmap of null values
- Maximum and minimum average prices per year in England
- Maximum and minimum number of crimes per area
- Count of records with average price below 100,000 per area

## Conclusion

This analysis provides insights into the housing market trends in London, highlighting variations in house prices and crime rates over the years.

## Requirements

- Python
- Pandas
- Matplotlib
- Seaborn
