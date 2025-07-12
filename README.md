# 🛍️ Sales Data Analysis using Pandas and Matplotlib

This project performs an exploratory data analysis on sales data using **Pandas** and **Matplotlib** in Python. It is inspired by and follows the amazing tutorial by **Keith Galli**.

---

## 📌 Project Objective

The goal is to clean and explore the dataset to answer several key business questions using data analysis and visualization techniques.

---

## 🧹 Data Cleaning Tasks

We begin by cleaning the raw sales data. Steps include:

- 🔻 Dropping rows with **NaN values** from the DataFrame.
- ❌ Removing rows based on **invalid or missing conditions**.
- 🔄 Converting columns to appropriate types using:
  - `pd.to_numeric()`
  - `pd.to_datetime()`
  - `.astype()`

---

## 🔎 Business Questions Answered

After cleaning the data, we explored and answered the following business questions:

1. 📅 **What was the best month for sales?**  
   → How much revenue was generated in that month?

2. 🌆 **Which city had the highest number of sales?**  
   → City-based analysis to identify top-performing locations.

3. ⏰ **What time should advertisements be displayed to maximize purchases?**  
   → Hourly trends to target customer behavior.

4. 📦 **What products are most often sold together?**  
   → Product bundling insights using grouped transactions.

5. 🥇 **What product sold the most and why?**  
   → Identify top-selling products and potential reasons behind their popularity.

---

## 🛠️ Methods and Techniques Used

To answer these questions, we used a variety of **Pandas** and **Matplotlib** functions:

- 🗂️ Merging multiple CSV files using `pd.concat()`.
- ➕ Creating new columns from existing ones.
- 🔤 Parsing strings using `.str` methods.
- 🧠 Applying custom logic with `.apply()`.
- 🔢 Grouping data with `.groupby()` for aggregation.
- 📊 Creating **bar charts** and **line graphs** for insights.
- 🏷️ Labeling graphs clearly to improve readability.

---

## 📈 Sample Visualizations

Graphs include:

- Monthly revenue trends
- Sales by city
- Hourly order frequency
- Top product combinations
- Best-selling product bar chart

---

## 📁 Dataset

The dataset used in this project was provided by [Keith Galli](https://github.com/KeithGalli) and includes monthly sales CSV files (e.g., `Sales_April_2019.csv`, `Sales_May_2019.csv`, etc.).

---
