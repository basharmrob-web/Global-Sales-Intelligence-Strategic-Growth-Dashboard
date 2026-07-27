# 📊 Executive Sales & Growth Intelligence Dashboard

A comprehensive Power BI business intelligence solution designed for executive oversight, tracking sales performance, geographical distribution, customer behavior, and predictive growth forecasts.

---

## 🌟 Dashboard Overview & Architecture

This Power BI project consists of three core interactive analytical pages (tabs):

### 1. 📈 Sales Performance Dashboard (Executive Overview)
* **Purpose:** Provides a high-level summary of financial health, order volumes, returns, and target achievements.
* **Key Metrics Cards:**
  * **Total Customers:** 4K
  * **Total Orders:** 19K
  * **Total Returns Value:** 420.19K
  * **Total Revenue:** 7.28M (vs. Target: 8.74M)
* **Visualizations:**
  * **Revenue Trend Over Time:** Monthly progression showing peak sales periods.
  * **Revenue vs. Target Gauge:** Visual progress tracker toward the 8.74M financial objective.
  * **Top 10 Products by Returns Value:** Pinpoints products experiencing high returns (e.g., Manual adjustments, Medium Ceramic Top Storage Jar, Postage).

### 2. 🌍 Customer & Geographical Analysis
* **Purpose:** Analyzes market reach, customer lifetime value, and top-performing regions/products.
* **Key Metrics Cards:**
  * **Total Customers:** 4K
  * **AOV (Average Order Value):** 376.13
* **Visualizations:**
  * **Top 7 Countries by Revenue:** Led heavily by the United Kingdom (~5.9M), followed by Netherlands, EIRE, Germany, France, Australia, and Switzerland.
  * **Revenue Share by Country (Donut Charts):** Detailed breakdown of regional contributions (UK holding ~81.18%).
  * **Top 10 Customers by Revenue:** Identifies high-value enterprise or repeat buyers.
  * **Top 5 Products by Revenue:** Funnel/bar distribution showcasing top revenue-generating items.

### 3. 🔮 Future Projections & Growth Forecast
* **Purpose:** Leverages predictive modeling and time-series forecasting to anticipate future revenue streams and order trends.
* **Key Metrics Cards:**
  * **Projected AOV:** 394.94
  * **YoY Growth %:** 1213.40%
  * **Projected Revenue:** 8.38M
* **Visualizations:**
  * **Forecast Total Revenue & Orders by Month:** AI-driven confidence intervals projecting future monthly trajectories.
  * **Monthly Forecast Table:** Granular tabular breakdown pairing historical/current months with forward-looking revenue and order estimates.

---

## 🛠️ Tech Stack & Tools
* **BI Tool:** Microsoft Power BI Desktop
* **Data Modeling:** Star Schema / Relational Modeling
* **Data Visualization:** Custom themes, KPI Cards, Line Charts, Gauge Charts, Donut Charts, Funnel & Decomposition Trees
* **Calculations:** DAX (Data Analysis Expressions) for metrics like AOV, YoY Growth, and Target variances.

---

## 📥 Filters & Interactivity
All dashboards feature global slicers in the top-right corner allowing stakeholders to dynamically slice data by:
* **Country** (All / Specific regions)
* **Year / Quarter** (Time-based filtering)

---
*Created as part of an Advanced Business Intelligence & Data Analytics Portfolio.*
