# Walmart Sales Performance Dashboard

## Project Summary

This README provides a concise summary of the Walmart Sales Performance Dashboard project, outlining its objective, data used, key sections, and the insights it delivers.

---

### **1. Project Objective**

The primary goal of this project was to design and implement an **interactive dashboard** for business stakeholders. This dashboard aims to provide clear, actionable insights into Walmart's weekly sales performance.

**Key Goals:**
* Monitor overall sales trends over time.
* Identify top-performing individual stores.
* Understand the specific impact of holiday weeks on sales figures.
* Explore potential relationships between sales and various external economic factors such as unemployment rates and fuel prices.

---

### **2. Data Overview & Tools**

**Data Source:**
* **Walmart Weekly Sales Data (`Walmart_Sales.csv`)**
    * This dataset contains historical weekly sales figures, complemented by information such as store ID, date of the sales record, a flag indicating holiday weeks, average temperature, fuel price, Consumer Price Index (CPI), and the unemployment rate in the region.

**Tools Used:**
* **Python (Pandas):** Utilized for initial data preparation and cleaning, including ensuring correct date formats, identifying and handling missing values, and treating duplicate records.
* **Tableau:** Employed for creating the interactive visualizations and assembling the final dashboard, allowing for dynamic exploration of the data.

---

### **3. Key Dashboard Sections & KPIs**

The dashboard is intuitively organized to offer a comprehensive and easy-to-understand view of sales performance. It includes:

#### **Key Performance Indicators (KPIs):**
* **Total Weekly Sales:** A prominent display showing the overall aggregated sum of sales across all stores and the entire recorded period.
* **Average Weekly Sales:** A clear card indicating the average weekly sales figure, providing a baseline understanding.

#### **Core Visualizations:**
* **Weekly Sales Trend:** A **Line Chart** that visualizes `Weekly_Sales` over `Date`, effectively revealing seasonal patterns, growth trajectories, or declines in sales performance over time.
* **Sales by Store:** A **Bar Chart** that highlights and compares sales performance across individual Walmart stores, typically sorted to quickly identify the highest-performing locations.
* **Sales by Holiday/Non-Holiday:** A **Bar Chart** dedicated to comparing total sales during holiday weeks (flagged as '1') versus non-holiday weeks (flagged as '0'), showcasing the direct impact of holidays.
* **Sales vs. Economic Factors (e.g., Unemployment/Temperature):** An **Exploratory Chart** (such as a Scatter Plot) designed to visualize potential correlations or relationships between `Weekly_Sales` and external factors like `Unemployment` rate or `Temperature`.

---

### **4. Key Insights & Findings**

Based on the analysis presented in the dashboard, several key observations can be made:

* **Overall Sales Performance:** The dashboard clearly indicates a [State the total sales number from your dashboard, e.g., "robust overall sales of $X million"] across the analyzed period.
* **Sales Trends:** [Describe the trend you observe, e.g., "Sales consistently show an upward trend year-over-year, suggesting stable growth," or "There are distinct seasonal peaks, especially around year-end, indicating strong holiday shopping periods."].
* **Holiday Impact:** [State your specific finding, e.g., "Holiday weeks consistently demonstrate a significant uplift in sales, often increasing weekly revenue by X% compared to non-holiday periods, underscoring their strategic importance for marketing and inventory planning."].
* **Top Performing Stores:** [Mention 1-2 top store IDs or a general observation, e.g., "Stores 10, 20, and 30 consistently lead in weekly sales, potentially due to their location, customer base, or operational efficiency. Further investigation into these stores could reveal best practices."].
* **Economic Influence:** [If you found a a correlation, state it, e.g., "An inverse relationship appears between unemployment rates and weekly sales; as unemployment decreases, sales tend to rise, suggesting consumer confidence plays a role." Or "While some economic factors are present, temperature does not show a clear direct correlation with sales trends."].

---

### **5. Interactivity & Recommendations**

The dashboard is built with interactivity in mind to empower stakeholders for deeper data exploration.

#### **Interactive Features:**
* **Filters/Slicers:** Users can dynamically filter the entire dashboard by `Date Range`, `Store ID`, and `Holiday/Non-Holiday` status. This allows for granular analysis of specific periods or locations.
* **Click-to-Filter (Actions):** Charts can be configured to act as filters. For instance, clicking on a specific store in the "Sales by Store" chart will automatically update all other relevant charts on the dashboard to show data exclusively for that selected store.

#### **Recommendations:**
* **Strategic Planning:** Leverage the insights on holiday sales to optimize inventory management, staffing levels, and marketing campaigns during anticipated peak periods.
* **Targeted Store Support:** Conduct further investigations into the factors contributing to the success of top-performing stores. Implement successful strategies from these stores across the wider network to boost overall performance.
* **Economic Monitoring:** Continue to track economic indicators like `Unemployment`, `CPI`, and `Fuel_Price` as they may provide leading insights into potential shifts in consumer spending and sales performance.

---
