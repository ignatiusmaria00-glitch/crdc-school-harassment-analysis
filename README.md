# 2015–16 CRDC School Harassment & Bullying Data Analysis

## Project Overview
This data analytics project analyzes the **2015–16 Civil Rights Data Collection (CRDC)** dataset to identify patterns, top-reporting geographic regions, and primary drivers of school-level harassment and bullying allegations across U.S. states. 

The goal was to transform raw, aggregated public health and education data into a clean, executive-ready dashboard to support data-driven decision-making and policy intervention insights.

---

## Tools & Skills Demonstrated
* **Tool:** Microsoft Excel / Excel for the Web
* **Data Hygiene & Preprocessing:** Removing duplicate national summaries, structural formatting, row deletion.
* **Data Aggregation:** PivotTables, dynamic value sorting, multi-metric summaries.
* **Data Visualization:** Rescaled Bar Charts, Stacked Bar Charts, Conditional Formatting.

---

## Data Quality & Methodology

1. **Structural Setup:** Converted raw data into structured Excel Tables with standardized headers.
2. **Data Integrity & De-duplication:** 
   * Identified and removed the national total summary row ("United States" = 135,192 allegations) from the main source table.
   * This eliminated double-counting in Grand Totals and fixed axis scaling distortions on chart visualizations (rescaling the primary axis from **160,000** down to a clean **25,000** max).
3. **Dynamic Value Filtering:** Configured PivotTable filters to dynamically isolate the Top 10 states by total volume.

---

## Key Findings

* **Top Reporting Volume:** **Illinois** ($19,687$) and **California** ($18,197$) reported the highest number of allegations, leading all states by a significant margin.
* **Category Drivers:** Across nearly all top-reporting states, allegations based on **Sex** and **Race/Color/National Origin** account for the largest proportion of reported incidents, followed by **Disability**.
* **Visual Optimization:** Converted a 50+ line clustered bar chart into a **Stacked Bar Chart**, consolidating 5 distinct allegation categories into a single, cohesive bar per state.

---

## Dashboard Visuals

*(Replace this placeholder with the screenshot of your final chart once uploaded to GitHub)*

![Top 10 States Stacked Bar Chart](<top 10_harassment_allegations.jpeg>)

---

## Repository Structure

```text
├── data/
│   └── Allegations-of-Harassment-or-Bullying.xlsx   # Main Excel Dataset
├── visuals/
│   └── dashboard_stacked_chart.png                 # Final Chart Export
└── README.md                                        # Project Documentation
