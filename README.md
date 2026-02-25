📊 Page View Time Series Visualizer
📌 Project Overview

This project analyzes and visualizes time-series data from the freeCodeCamp.org forum using Python.

The dataset contains the number of daily page views from:

📅 May 2016 – December 2019

The objective is to:

Clean and preprocess time-series data

Identify long-term growth trends

Detect seasonal patterns

Visualize insights using different types of plots

📂 Dataset Information

File: fcc-forum-pageviews.csv

Columns:

Column	Description
date	Date of forum page views
value	Number of page views on that date
🧹 Data Cleaning

To ensure accurate visualization:

Removed the top 2.5% of page view values

Removed the bottom 2.5% of page view values

This eliminates extreme outliers that could distort the visual trends.

📈 Visualizations Created
1️⃣ Line Plot

Shows daily page views over time.

Title:
Daily freeCodeCamp Forum Page Views 5/2016-12/2019

Purpose:

Identify long-term growth

Observe spikes and fluctuations

Track community expansion

2️⃣ Bar Plot

Displays average monthly page views grouped by year.

X-axis: Years
Y-axis: Average Page Views
Legend: Months

Purpose:

Compare yearly growth

Analyze monthly performance trends

3️⃣ Box Plots

Two box plots are created:

📦 Year-wise Box Plot (Trend)

Shows distribution of page views per year

Highlights growth consistency and variability

📦 Month-wise Box Plot (Seasonality)

Shows distribution of page views per month

Helps detect seasonal trends and recurring patterns

🛠 Technologies Used

Python

Pandas

Matplotlib

Seaborn

▶ How To Run

1️⃣ Install Dependencies

pip install pandas matplotlib seaborn

2️⃣ Run Project

python main.py

