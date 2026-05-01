# 🛒 Sales Analysis of France — Retail Performance Dashboard

> **Tool:** Tableau Desktop &nbsp;|&nbsp; **Domain:** Retail Analytics &nbsp;|&nbsp; **Dashboards:** 2

A two-dashboard Tableau project analysing the sales performance, profitability, and customer behaviour of a French retail chain across multiple years, stores, and product lines.

---

## 📊 Project Overview

This project explores a large-scale French retail dataset to uncover the drivers behind a deeply negative profit margin, identify high-performing stores and products, and segment customers by demographics and spending behaviour. The analysis spans over **1.6 million customers**, **€25.9M in total revenue**, and data from **2007 to 2012**.

---

## 🖥️ Dashboard 1 — Sales Performance & Trends

<img width="1512" height="791" alt="image" src="https://github.com/user-attachments/assets/ad9ea41f-f3b2-46f5-9adb-c1264f343497" />


### Key Metrics
| Metric | Value |
|---|---|
| Total Revenue | €25,926,743 |
| Total Margin | -€31,142,844 |
| Profit Margin | **-120.12%** |

### Charts Included

**Revenue vs Margin Trend (2007–2012)**
Bar + line dual-axis chart tracking annual revenue (bars) against margin (line). Revenue peaked in 2010 before declining; margin remained consistently negative, signalling structural cost issues rather than a revenue problem.

**Revenue by Month**
Combined bar + line chart revealing strong seasonality — Month 5 (May) and Month 12 (December) show the highest revenue spikes, while profit margin deepens most in December, suggesting heavy discounting during peak sales periods.

**Store Performance (Scatter Plot)**
Each circle represents a store plotted by Total Revenue (Y) vs Margin (X), colour-coded by margin health. A clear cluster of high-revenue but deeply loss-making stores sits in the upper-left quadrant, identifying stores that generate volume but destroy value. Reference lines mark the company average on both axes.

**Product Revenue (Scatter Plot)**
Products mapped by Margin Ratio (X) vs Total Revenue (Y). Top revenue products (€506K, €411K) sit near zero or positive margin — these are the business's healthiest SKUs. Products in the negative margin ratio zone represent candidates for repricing or discontinuation.

---

## 👥 Dashboard 2 — Customer & Product Analysis

<img width="1512" height="788" alt="image" src="https://github.com/user-attachments/assets/bab41559-070d-4014-b2b7-a249dfb92bb8" />

### Key Metrics
| Metric | Value |
|---|---|
| Total Customers | 1,614,485 |
| Revenue Per Customer | €21.01 |
| Profit Margin | **-83.75%** |

### Charts Included

**Revenue & Margin by Age Group**
The **51–65 age group** generates the highest revenue (~€250M) and is the company's most valuable segment. The 18–25 and 26–30 groups contribute the least. Profit margin (line) stays flat across all groups — the margin problem is company-wide, not segment-specific.

**Revenue Distribution (Histogram)**
Right-skewed distribution showing that the vast majority of customers spend between €0–€580, with a long tail of higher spenders. The mode bin sits around €290–€435, indicating a mid-value customer base.

**Margin by Civility (Pie Chart)**
Breakdown by customer title: **Madame (44.24%)** and **Monsieur (37.32%)** are the two main groups, with a significant **INCONNU (Unknown, 18.44%)** segment — a data quality flag worth investigating. All three groups share negative margins proportionally.

**Top 10 Customers by Revenue**
Bar chart of the ten highest-spending individual customers. **PIERRE** leads significantly at ~€13K lifetime value, followed by KAMAL, ALEXANDRU, and LYDIE around €8K each. Useful for loyalty programme targeting.

**Product Profitability (Scatter Plot)**
SKUs plotted by Amount (X) vs Margin (Y). **FSAGTRIM** and **BTFNEO23H** anchor the top-right as high-revenue, near-zero margin products. **ORWPM4** is an outlier — high amount but the worst margin of any product (-€1M+), making it the single most value-destructive SKU in the catalogue.

**Cashier Performance Analysis (Scatter Plot)**
Individual cashiers (IDs) plotted by sales Amount vs Margin. Two standout cashiers (**908102** and **912621**) handle the highest volume. Most cashiers cluster near the average on both axes. Negative-margin cashiers in the lower quadrant may indicate excessive discounting at point of sale.

---

## 💡 Key Business Insights

1. **The margin problem is structural, not seasonal.** Revenue peaked in 2010–2011 but margin was already deeply negative from 2007. Cost of goods, not sales volume, is the primary issue.
2. **December sells the most — and loses the most margin.** Holiday discounting likely amplifies the margin gap in Month 12.
3. **ORWPM4 is a priority for repricing or discontinuation.** It is the single most margin-destructive product despite strong sales volume.
4. **The 51–65 demographic drives the most revenue** — any loyalty or upsell strategy should prioritise this group.
5. **18.44% of customer records have unknown civility** — a data hygiene issue that could affect demographic segmentation accuracy.
6. **Two cashiers (908102, 912621) are outliers** in volume — worth investigating whether their margin profile is also above or below average.

---

## 🗂️ Repository Structure

```
📁 Sales-Analysis-France/
├── Dashboard1.twbx          # Sales Performance & Trends
├── Dashboard2.twbx          # Customer & Product Analysis
├── dashboard1.png           # Dashboard 1 screenshot
├── dashboard2.png           # Dashboard 2 screenshot
└── README.md
```

---

## 🛠️ Tools & Skills Demonstrated

- **Tableau Desktop** — dual-axis charts, scatter plots with reference lines, pie charts, histograms, KPI tiles
- **Retail data analysis** — margin decomposition, customer segmentation, product profitability
- **Data storytelling** — translating raw transactional data into actionable business insights
- **Large dataset handling** — 1.6M+ customer records across 5+ years

---

## 👤 Author

**Harsh Prajapati** &nbsp;|&nbsp; [github.com/harshbaee](https://github.com/harshbaee) &nbsp;|&nbsp; [linkedin.com/in/harsh2783](https://linkedin.com/in/harsh2783)
