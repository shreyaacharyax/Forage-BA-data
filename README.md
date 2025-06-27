# Forage-BA-data

This repository contains my work from the Forage British Airways Data Science Virtual Experience. It covers real-world challenges including predictive modeling for customer acquisition. The notebooks and presentation showcase data cleaning, sentiment analysis, topic modeling, and predictive analytics within a dynamic airline setting.

## Project Overview

This project focuses on analyzing an airline dataset to understand how different flight routes relate to the likelihood of customers completing their bookings. The analysis aims to support strategic decision-making by identifying patterns and trends across various routes.

## Objective

- To determine whether certain routes are associated with higher or lower booking completion rates.  
- The findings can provide actionable insights for route optimization, marketing strategies, and improving overall booking efficiency.

## Methodology

- Data was loaded and explored using `pandas` and `seaborn`.
- Initial inspection involved checking for null values and understanding the distribution of key variables.
- Attempted to visualize the relationship between `route` (categorical) and `booking_complete` (binary) using Seaborn.
- Used `jointplot(kind='kde')` initially but it raised an error due to `route` being categorical.
- Recognized the importance of selecting visualization methods appropriate for data types.
- Adjusted the approach by exploring route-level booking completion trends with group-based summaries instead of KDE plots.

## Key Learnings

- KDE (Kernel Density Estimation) requires continuous variables, so categorical data like `route` cannot be used with it.
- Choosing the right visualization based on variable types is critical.
- Aggregating booking completions by route yields clearer and more interpretable results than jointplots or heatmaps in this case.

## Deliverables

- PowerPoint presentation summarizing key insights from the analysis.
- Visualizations interpreting booking trends across different flight routes.
- Recommendations based on observed booking behavior.

## Tools Used

- Python (`pandas`, `seaborn`, `matplotlib`)  
- Google Colab Notebook (for analysis)  
- PowerPoint (for presenting results)  
