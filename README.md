🥑 Avocado Price Optimization using Data Science & Mathematical Modeling

Colab Link: https://colab.research.google.com/drive/1KL54NqcAv34x-jsH-_BkuIq7BEdFKNTv

This project demonstrates how to use data analytics, regression modeling, and mathematical optimization to determine the optimal price and supply of avocados that maximize net revenue.
It follows a complete pipeline — from data exploration to predictive modeling and finally prescriptive optimization.

📘 Project Overview

The notebook walks through a 3-stage decision-making framework:

Descriptive Analytics – Explore real avocado sales data from the Hass Avocado Board
:

Analyze trends over years and seasons.

Study correlations between price, sales, and regions.

Visualize market behavior using Seaborn and Matplotlib.

Predictive Analytics – Build a regression model (using statsmodels and scikit-learn) to estimate avocado demand as a function of:

Price

Region

Year

Seasonality

Prescriptive Analytics – Formulate and solve a price optimization problem using Gurobi:

Decision variables: price and quantity supplied per region.

Objective: maximize total revenue considering costs and wastage.

Constraints: production limits, regional demand, and business rules.
