# Page-View-Time-Series-Visualizer

#  Time Series Visualizer

This project visualizes time series data of daily page views from the freeCodeCamp.org forum using **Pandas**, **Matplotlib**, and **Seaborn**. The data spans from **2016-05-09 to 2019-12-03**.

The visualizations provide insight into trends, seasonality, and fluctuations in user activity on the forum over time.

---

##  Dataset

- **Source**: freeCodeCamp Public Dataset
- **Download**: [fcc-forum-pageviews.csv](https://raw.githubusercontent.com/freeCodeCamp/boilerplate-page-view-time-series-visualizer/master/fcc-forum-pageviews.csv)

---

##  Features & Visualizations

###  1. Line Plot
- Visualizes raw daily page views over time.
- Includes:
  - **30-Day Moving Average** line.
  - **Highlighted Weekends** (in orange).
  - **Highlighted Holidays** (in red, starred).
- 📍 Title: `Daily freeCodeCamp Forum Page Views (with 30-Day MA, Weekends & Holidays)`

###  2. Bar Plot
- Displays **monthly average page views** grouped by **year**.
- 📍 X-axis: Years
- 📍 Y-axis: Average Page Views
- 📍 Legend: Month names

###  3. Box Plots
- Two box plots for distribution analysis:
  - **Year-wise**: Understand trends over the years.
  - **Month-wise**: Understand seasonal patterns across months.
-  Shows outliers and quartiles.

---

##  Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
