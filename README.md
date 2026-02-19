

Sales Data Analysis using Pandas
Objective:

The objective of this project is to analyze sales data from a CSV file using Pandas and visualize key business insights using charts.

Tools Used:

Python

Pandas

Matplotlib

Google Colab

Dataset Description

The dataset contains the following columns:

Date – Date of sale

Product – Product name

Quantity – Number of units sold

Price – Price per unit

A new column Total was created to calculate revenue:

Total = Quantity × Price

Analysis Performed
1. Total Revenue by Product

Used:

groupby("Product").sum()


This helped identify which product generated the highest revenue.

Observation:
Laptop generated the highest revenue compared to other products.

2. Total Revenue by Date

Used:

groupby("Date").sum()


This helped analyze daily revenue trends.

Observation:
Revenue decreased over the observed dates, indicating possible variation in sales demand.

Visualizations:

Bar chart showing revenue by product

Line chart showing revenue by date

These visualizations help quickly understand performance trends.

How to Run:

Open the notebook in Google Colab or Jupyter.

Run cells sequentially.

Charts and analysis outputs will be generated automatically.
