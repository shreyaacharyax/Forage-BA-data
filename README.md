# Forage-BA-data
This repo contains my work from the Forage British Airways Data Science Virtual Experience. It covers real-world challenges including predictive modeling for customer acquisition. The notebooks and presentation showcase data cleaning, sentiment analysis, topic modeling, and predictive analytics in a dynamic airline setting.

Project Overview
This project focuses on analyzing an airline dataset to understand how different flight routes relate to the likelihood of customers completing their bookings. The analysis aims to support strategic decision-making by identifying patterns and trends across various routes.

Objective
To determine whether certain routes are associated with higher or lower booking completion rates. The outcome of this analysis can provide actionable insights for route optimization, marketing strategies, and improving overall booking efficiency.

Methodology
The data was loaded and explored using pandas and seaborn.

Initial inspection involved checking null values and understanding the distribution of key variables.

Attempted to visualize the relationship between route (categorical) and booking_complete (binary) using Seaborn.

A jointplot(kind='kde') was initially used but returned an error due to route being categorical.

This highlighted the importance of selecting appropriate visualization methods based on data types.

Adjusted approach to explore route-level booking completion trends using group-based summaries instead of KDE plots.

Key Learnings
Categorical data such as flight routes cannot be plotted using KDE (Kernel Density Estimation) which is meant for continuous variables.

Choosing the right visualization technique based on variable types is critical.

Aggregating booking completions by route provides more meaningful and interpretable results than using jointplots or heatmaps.

Deliverables
A PowerPoint presentation summarizing key insights from the data analysis

Visualizations and interpretation of booking trends across different flight routes

Recommendations based on observed booking behaviors

Tools Used
Python (pandas, seaborn, matplotlib)

Google Colab Notebook (for analysis)

PowerPoint (for results presentation)

