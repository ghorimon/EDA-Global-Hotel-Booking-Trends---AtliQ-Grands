# EDA-Global-Hotel-Booking-Trends---AtliQ-Grands

## Project Status & Tech Stack
[![Project Status](https://img.shields.io/badge/Status-Analysis%20Complete-brightgreen)](https://github.com/harsh-dataanalyst/atliq-hotels-data-analysis)
[![Analysis Period](https://img.shields.io/badge/Data%20Period-May%20'22%20--%20Aug%20'22-blue)](https://github.com/harsh-dataanalyst/atliq-hotels-data-analysis)
[![Language](https://img.shields.io/badge/Language-Python-informational)](https://www.python.org/)
[![Tools](https://img.shields.io/badge/Tools-Jupyter%20Notebook%20%7C%20Pandas%20%7C%20Matplotlib-yellow)](https://jupyter.org/)
[![Domain](https://img.shields.io/badge/Domain-Hospitality%20%2F%20Hotel-red)](https://github.com/harsh-dataanalyst/atliq-hotels-data-analysis)

---

## 🌟 Project Overview

This repository contains a comprehensive **Data-Driven Business Performance Analysis** for **AtliQ Hotels**, a premium luxury hotel chain operating across major Indian cities (Mumbai, Delhi, Hyderabad, and Bangalore).

Facing a critical decline in bookings and overall revenue, the objective was to dive deep into historical booking and operational data to diagnose the root causes, evaluate operational efficiency, and deliver **actionable business recommendations** to management.

---

## 🎯 The Business Challenge & Goal

### Problem Statement
Despite its strong brand positioning, AtliQ Hotels experienced a significant **drop in business performance** across its properties. The management needed a detailed diagnosis of the historical data (May 2022 to August 2022) to understand where revenue was leaking and how to optimize capacity and pricing strategies.

### Project Objective
1.  **Diagnose Performance:** Uncover the root causes of the decline in bookings and revenue.
2.  **Evaluate Operations:** Assess capacity utilization, and identify patterns of overbooking or under-utilization.
3.  **Identify Trends:** Analyze customer behavior, popular room categories, and the performance of various booking platforms.
4.  **Actionable Insights:** Generate data-backed insights to inform strategic planning and reverse the negative performance trend.

---

## 📊 Key Insights & Business Recommendations

The analysis yielded several critical findings that directly address the management's concerns:

| Area of Analysis | Key Insight Generated | Operational Recommendation Example |
| :--- | :--- | :--- |
| **Occupancy & Demand** | Identified cities and properties with the **highest and lowest occupancy rates**, highlighting regional disparities in demand. | Allocate marketing budgets strategically to underperforming cities like [CITY NAME, find in your results]. |
| **Operational Efficiency** | Detected patterns of **overbookings** and **under-utilization** on specific days, pointing to poor inventory management. | Adjust inventory allocation models, especially for high-demand properties on weekends. |
| **Revenue Channels** | Ranked performance of **room categories** and **booking platforms** (e.g., MakeMyTrip vs. Goibibo). | Optimize commission rates with underperforming platforms or adjust pricing for top-performing room categories. |
| **Customer Behavior** | Revealed key booking trends and customer preferences over the four-month period. | Tailor loyalty programs based on observed booking patterns (e.g., length of stay, lead time). |

***(Note: Replace bracketed text like `[CITY NAME, find in your results]` with actual findings from your notebook.)***

---

## 🛠️ Data Analysis & Methodology

The project followed a robust Data Analysis workflow executed entirely in the **`atliq_hotels_data_analysis.ipynb`** Jupyter Notebook:

1.  **Data Import & Exploration (EDA):** Loaded and inspected six distinct dimension and fact tables, focusing on initial data quality assessment (distributions, missing values, data types) using **Pandas**.
2.  **Data Cleaning & Preprocessing:** Handled invalid entries, addressed outliers, and ensured data integrity across all tables.
3.  **Data Transformation & Feature Engineering:**
    * Merged dimensional and fact tables (`dim_date`, `dim_hotels`, `fact_bookings`, etc.) using SQL-like joins.
    * Calculated crucial business metrics, including the creation of the **`occupancy_percentage`** column.
4.  **Insight Generation:** Performed detailed group-by analysis, time-series analysis, and leveraged **Matplotlib** for visualization to translate complex data into clear, actionable business insights.

---

## 📚 Datasets Used (Data Schema)

The project utilized six interconnected CSV files (dimension and fact tables) covering the booking and operational data:

| File Name | Data Type | Description |
| :--- | :--- | :--- |
| `fact_bookings.csv` | Fact | Detailed, unaggregated booking-level data (transactional). |
| `fact_aggregated_bookings.csv` | Fact | Daily aggregated booking data (summary). |
| `new_data_august.csv` | Fact | Extension data for August 2022 to provide a full four-month period. |
| `dim_hotels.csv` | Dimension | Hotel metadata (cities, property type). |
| `dim_rooms.csv` | Dimension | Room category and capacity information. |
| `dim_date.csv` | Dimension | Date-related dimension table for time-series analysis. |

---

## 💻 Tech Stack

| Tool | Purpose |
| :--- | :--- |
| **Python** | Primary scripting language. |
| **Jupyter Notebook** | Development environment for interactive code execution and analysis. |
| **Pandas** | Data wrangling and manipulation. |
| **NumPy** | Numerical operations and array handling. |
| **Matplotlib** | Data visualization and charting. |
| **Git / GitHub** | Version control and collaboration. |

---

## 📧 Connect with the Author

This project was developed by:

**Harsh Gupta**

* 🔗 **LinkedIn:** [linkedin.com/in/hganalyst](https://www.linkedin.com/in/rimonghosh)
* 📧 **Email:** [harshgupta11x@gmail.com](mailto:rimonsarbajitghosh@gmail.com)

Feel free to connect or drop a message about the analysis!
