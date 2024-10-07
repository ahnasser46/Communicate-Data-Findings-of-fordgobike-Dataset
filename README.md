# Ford Go Bike Exploration and Explanatory Project

## Project Overview

This project is part of the Advanced Data Analysis Nanodegree by Udacity. This project is divided into two parts:

1. **Exploratory Data Analysis (EDA)**: In this phase, I performed an analysis using Python to explore variables and uncover patterns, relationships, and oddities in a chosen dataset. The process involved examining univariate and multivariate relationships, documenting findings, and being patient with exploration.

2. **Explanatory Analysis**: Based on the findings from EDA, I created a polished slide deck to communicate the most significant insights. The focus was on using relevant visualizations to tell a clear story of the key results discovered in the analysis.

## Dataset

The dataset contains 183,412 rows and 16 columns, with a mix of categorical and quantitative data. Some columns include null or non-meaningful values, which required handling during analysis. Additional columns were derived from the existing data to assist in exploring relationships between variables. Since the dataset spans just one or two months, the exploration focuses on a detailed analysis within that specific time frame.




## Summary of Findings

Key points of interest include analyzing when and where most trips started, and observing how younger riders tend to take longer trips. Using the coordinates data, I explored trip distances. Additional columns like age, distance, day of the week, and trip sequence were created to further investigate patterns. Multiple plots were generated to provide detailed insights. I examined numeric variables for correlations and analyzed their relationships with qualitative factors such as weekdays, time of day, and month days. Log transformations were applied to improve the visualization of numeric data, and data wrangling steps were taken to filter out irrelevant values, ensuring accurate analysis. 


## Key Insights for Presentation

For the explanatory part, I focused on analyzing the relationship between distance, duration, and age. I started by using a logarithmic scale to plot their distributions through histograms. Then, by examining weekdays and day periods, I identified which days and times had the longest average distances traveled and durations taken, using line, scatter, and bar plots. The data revealed interesting variations in trip patterns across different days. Notably, I found that the periods with the longest distances traveled were also the ones with the shortest trip durations.