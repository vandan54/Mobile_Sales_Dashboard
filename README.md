# Mobile Sales Performance & Temporal Analysis Dashboard

A comprehensive, interactive Power BI data analytics solution designed to monitor retail mobile sales pipelines. This project focuses on high-level operational metrics, Month-to-Date (MTD) performance tracking, and granular Year-over-Year (YoY) temporal comparisons to drive strategic supply chain and sales decisions.

---

## 📊 Dashboard Previews

### 1. Main Executive Dashboard
Provides a macro overview of core performance KPIs, top brands, regional delivery matrices, and product category distributions.
<img width="1323" height="745" alt="image" src="https://github.com/user-attachments/assets/a096d8eb-f556-4c5e-85dc-410708ea90f9" />


### 2. Month-to-Date (MTD) Report
Features high-frequency time-series tracking across custom calendars, allowing stakeholders to monitor daily run rates and month-specific sales velocity.
<img width="1445" height="751" alt="image" src="https://github.com/user-attachments/assets/503e648b-e991-4184-aff8-44b865426fad" />


### 3. Same Period Last Year (YoY Benchmarking)
An analytical deep-dive comparing current-period sales performance against corresponding historical timeframes broken down by Year, Quarter, and Month.
<img width="1326" height="750" alt="image" src="https://github.com/user-attachments/assets/fc6b5663-4aa1-4aec-b97c-1d84eb7b9da2" />


---

## 🚀 Key Features & Analytical Insights

* **Macro Performance Metrics:** Instantly tracks global sales value (769M), Total Units Sold (19K), Transaction Counts (4K), and an overall brand itemization threshold (40.11K).
* **Brand & Model Dominance Analysis:** 
  * Identifies market leaders via structured data cards (Apple leading revenue at 161.6M across 783 transactions, followed closely by OnePlus and Samsung).
  * Maps popular handset variations (iPhone SE leading at 60M, followed by OnePlus Nord and Galaxy Note 20).
* **Geographic & Logistics Distribution:** Spotlights major urban performance hubs (Delhi and Mumbai leading overall sales volume) alongside a weekly distribution engine (Monday and Friday capturing top sales days).
* **Fulfillment & Customer Trust Mapping:** Tracks channel usage via payment mode pie charts (Cash, Credit Card, Debit Card, and UPI distributed evenly near ~24-26% chunks) paired with customer evaluation metrics (100% classified into Good, Average, and Poor buckets).
* **Granular Time-Intelligence & MTD Tracking:** 
  * Leverages dense, daily time-series analysis to plot transaction momentum over months like March, May, and September.
  * Compares historical performance side-by-side using side-by-side dual bar charts to evaluate exact cyclical trends across equivalent quarters (Q1–Q4) and months.
* **Left-Hand Unified UI Controls:** Incorporates a streamlined, persistent side panel containing vertical, clickable calendar slicers (January through October) for fast filtering.

---

## 🛠️ Technical Stack & Methods Used
* **Platform:** Power BI Desktop
* **DAX Time Intelligence Expressions:** Custom `TOTALMTD`, `SAMEPERIODLASTYEAR`, and period-over-period variance calculation algorithms to compute parallel tracking trends.

---

## 📁 Repository Structure
* `MS_Dashboard -.pbix` — The master interactive multi-page Power BI report.
* `Filter.png` / `Quanity.png` / `Transactions.png` — Dashboard visual screenshots and visual assets.
