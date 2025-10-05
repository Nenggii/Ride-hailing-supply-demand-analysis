# Ride-Hailing Supply-Demand Balance Analysis

## Project Overview 📊

This project conducts a comprehensive analysis of **supply and demand dynamics** for a ride-hailing service in a single city. Utilizing one week of granular, hourly data, the goal is to provide data-driven recommendations to management on **pricing, driver incentives, and optimal driver deployment** to improve market efficiency and rider experience (coverage).

The entire analysis, including all data manipulation, calculations, visualizations, and final answers, was performed within a **single Excel workbook**.

---

## Deliverables (Q1 - Q7)

The repository contains the final analysis spreadsheet (e.g., `Bolt Task Analysis.xlsx`), which includes seven distinct sheets addressing the core business questions:

| Sheet | Business Question & Focus | Key Output |
| :--- | :--- | :--- |
| **Q1** | **Demand Analysis**: Calculate total unique searches and visualize demand patterns in a **24x7 grid**. | Pivot table showing hourly and daily demand distribution. |
| **Q2** | **Demand & Supply Chart**: Illustrate the hourly balance/imbalance between rider searches (Demand) and total driver hours (Supply) across the week. | A line chart of Demand vs. Supply over the 7-day period. |
| **Q3** | **Coverage Heatmap**: Visualize the **Coverage Ratio** (the percentage of users who saw a car) in a **24x7 grid** for drivers to identify high-demand (low-coverage) hours. | Heatmap showing low/high coverage times. |
| **Q4** | **Strategic Price Multipliers**: Propose a **weekly schedule of price multipliers** to increase supply and decrease demand during periods of low coverage. | A second 24x7 heatmap with specific price multiplier values (e.g., 1.2x, 1.5x). |
| **Q5** | **Incentive Budget**: Identify the **5-hour consecutive period with the highest demand** and calculate the maximum driver incentive budget by re-investing the full 20% commission revenue from that period. | Specific 5-hour window and calculated incentive budget (€). |
| **Q6** | **Maximum Trip Potential**: Estimate the total number of weekly trips the platform *could have finished* if the **Coverage Ratio was 100%** at all times. | Total estimated trips with max coverage. |
| **Q7** | **Driver Utilization**: Define and calculate the **5 most utilized hours** of the week, and calculate the sum of finished trips during those peak utilization times. | Definition of utilization and the 5 specific hours and finished ride count. |

---

## Data Sources

The analysis utilized two datasets provided at an hourly resolution for the period **November 7th to November 13th, 2016**.

| Dataset | Metric Represented | Key Fields Used |
| :--- | :--- | :--- |
| `Searches_raw.xlsx` | **Demand** (Rider activity) | `People saw 0 cars`, `People saw +1 cars`, `Coverage Ratio` |
| `Activity_raw.xlsx` | **Supply** (Driver activity) | `Online (h)`, `Finished Rides`, `Rides per online hour` |

---

## Technical Stack

* **Analysis Tool:** Microsoft Excel
* **Methodology:** Advanced Excel functions (Pivot Tables, `SUMIFS`, conditional formatting for heatmaps), and data visualization (Charts).

---

## How to Review the Project

1.  **Open the Excel File**: Open the main analysis workbook (e.g., `Bolt Task Analysis.xlsx`).
2.  **Review the Sheets**: Navigate through the sheets labeled **Q1** through **Q7** to see the raw data transformations, calculations, formulas, and final visualizations (charts and heatmaps) used to derive the answers.
