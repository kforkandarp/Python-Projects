# 📊 Sales Data Analysis

This repository contains code and insights derived from detailed analysis of a 2019 sales dataset. The analysis covers sales trends, product performance, regional distribution, and order value patterns.

---

## 📚 Table of Contents

* [🚀 Getting Started](#-getting-started)

  * [📦 Importing Libraries](#-importing-libraries)
  * [📂 Loading Data](#-loading-data)
  * [🧹 Data Processing](#-data-processing)
* [🔍 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)

  * [📈 Sales Trends](#-sales-trends)
  * [📦 Product Insights](#-product-insights)
  * [💰 Order Value Analysis](#-order-value-analysis)
  * [🌆 City-wise Revenue](#-city-wise-revenue)
  * [🗺️ State Distribution](#️-state-distribution)
* [✅ Conclusion](#-conclusion)

---

## 🚀 Getting Started

### 📦 Importing Libraries

All necessary Python libraries for data manipulation and visualization are imported (e.g., `pandas`, `matplotlib`, `seaborn`, `itertools`).

---

### 📂 Loading Data

The dataset includes **12 CSV files** representing sales data from **January to December 2019**.
Each file contains:

* `Order ID`
* `Product`
* `Quantity Ordered`
* `Price Each`
* `Order Date`
* `Purchase Address`

---

### 🧹 Data Processing

This stage involves:

* Merging monthly files into one dataset
* Handling missing data
* Converting data types
* Extracting features like `Month`, `City`, `Hour`, `Weekday` from `Order Date`

---

## 🔍 Exploratory Data Analysis (EDA)

### 📈 Sales Trends

#### ✅ Best Month for Sales

Identify the month with the highest revenue.

#### 📅 Day of the Week with Highest Sales

Analyze which day generates the most sales consistently.

#### 📆 Revenue by Weekday Timeline

Visualize sales trends over weekdays.

#### ⏰ Sales by Hour

Determine the hours with the highest customer activity.

---

### 📦 Product Insights

#### 🏆 Top-Selling Product

Which product had the highest quantity ordered?

#### 🏙️ Best-Selling Products by City

Compare top products in different cities.

#### 💸 Highest Revenue Products by City

List top 5 products generating the most revenue city-wise.

#### 🔗 Frequently Bought Together

Identify commonly bundled products using association analysis.

#### 📊 Multiple Product Orders

Calculate what percentage of orders included more than one item.

---

### 💰 Order Value Analysis

#### 🥇 Highest Single-Order Value

Identify the most valuable individual order.

---

### 🌆 City-wise Revenue

#### 🏙️ City with Highest Revenue

Determine which city contributed the most to total sales.

#### 🧾 City with Most Products Sold

Find out which city had the highest number of items sold.

---

### 🗺️ State Distribution

#### 📍 Distribution of Orders by State

Visualize the state-wise breakdown of all sales.

---

## ✅ Conclusion

Our comprehensive analysis of the 2019 sales data reveals several critical insights:

* 📅 **December** was the best-performing month.
* 🕑 **Peak hours** for purchases help identify ideal advertising windows.
* 🏙️ **San Francisco** topped revenue charts, while **AAA Batteries** sold the most.
* 🛒 Many customers purchase **bundled items**, a trend businesses can leverage.

These insights can guide strategic decisions in marketing, inventory management, and geographic targeting. Ongoing data monitoring is essential to maintain and expand market advantage.

