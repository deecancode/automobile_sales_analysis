# Automobile Sales Analysis

This repository contains a Jupyter Notebook for analyzing historical automobile sales data during recession and non-recession periods. The analysis includes various visualizations created using Matplotlib, Seaborn, and Folium.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Data Description](#data-description)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Contributors](#contributors)
- [License](#license)

## Introduction

In this project, we analyze historical automobile sales data to understand the impact of recession periods on automobile sales. The analysis includes creating various visualizations to gain insights into the data.

## Setup

To run this project, you need to have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- folium
- requests

You can install the required libraries using the following command:

pip install pandas numpy matplotlib seaborn folium requests


## Data Description

The dataset used for this analysis contains historical automobile sales data representing automobile sales and related variables during recession and non-recession periods. The dataset includes the following variables:

1. Date: The date of the observation.
2. Recession: A binary variable indicating recession period; 1 means it was a recession, 0 means it was normal.
3. Automobile_Sales: The number of vehicles sold during the period.
4. GDP: The per capita GDP value in USD.
5. Unemployment_Rate: The monthly unemployment rate.
6. Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
7. Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
8. Price: The average vehicle price during the period.
9. Advertising_Expenditure: The advertising expenditure of the company.
10. Vehicle_Type: The type of vehicles sold; Superminicar, Smallfamilycar, Mediumfamilycar, Executivecar, Sports.
11. Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
12. Month: Month of the observation extracted from Date.
13. Year: Year of the observation extracted from Date.

## Visualizations

The notebook includes the following visualizations:

1. Line chart showing how automobile sales fluctuate from year to year.
2. Line chart comparing sales trends between different vehicle types during recession periods.
3. Bar chart comparing sales trends during recession and non-recession periods.
4. Bubble plot displaying the impact of seasonality on automobile sales.
5. Scatter plot identifying the correlation between consumer confidence and automobile sales during recession periods.
6. Pie chart displaying the portion of advertising expenditure during recession and non-recession periods.
7. Pie chart displaying the total advertisement expenditure for each vehicle type during recession periods.
8. Line plot analyzing the effect of the unemployment rate on vehicle type and sales during the recession period.
9. Choropleth map showing the recession impact on various offices/city sales.


## Contributors

- [Dr. Pooja]- Initial Lab Creation
- [Sowmyaa Gurusamy] - Updated the lab instructions
- [Shengkai] - Created Lab Template
- Nabelou Ouologuem - Added code for downloading data and creating visualizations

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
