# 📊 Sales Insights Dashboard | Power BI

An interactive **Sales Analytics Dashboard** built with Microsoft Power BI to analyze sales performance, profitability, product categories, order sizes, price tiers, and regional distribution.

The project covers the process from **raw data preparation and cleaning to interactive business intelligence reporting**, with the goal of transforming sales data into clear and actionable insights.
---

## 🎯 Project Objective

The main objective of this project was to explore sales data and answer key business questions such as:

- How are total sales and profit performing?
- Which product categories generate the most sales?
- Which price tiers contribute most to revenue and profit?
- How does order size affect sales?
- Which regions generate the highest sales?
- Which products are the strongest profit contributors?
- What factors are influencing profitability?
- How are sales and profit changing over time?
---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query** – Data cleaning and transformation
- **DAX** – KPI calculations and measures
- **Data Visualization**
- **Decomposition Tree**
- **Key Influencers**
- **Treemap**
- **Interactive Slicers**
---

## 🔄 Data Analysis Workflow

### 1. Data Preparation

The raw sales data was prepared and cleaned before being used for analysis.

The preparation process included:

- Reviewing the raw dataset
- Cleaning and transforming data
- Checking data types and consistency
- Preparing fields required for analysis
- Creating calculated measures and analytical categories

---

### 2. KPI Development

The dashboard tracks several key business KPIs:

| KPI | Value |
| Total Sales | 138.41M |
| Total Profit | 55.61M |
| Total Cost | 82.81M |
| Profit Margin | 40.17% |
| Total Orders | 215K |
| Total Discount | 2.67M |

These KPIs provide a high-level overview of overall sales and profitability performance.
---

# 📈 Dashboard Pages

## 1. Sales Overview

The main dashboard provides an executive-level overview of sales performance.

### Key Visuals

- Total Sales
- Total Profit
- Total Cost
- Profit Margin
- Total Orders
- Total Discount
- Sales by Price Tier
- Sales by Order Size
- Sales by Product Category
- Sales & Profit Trend
- Top 10 Products by Profit
- Sales by Region

### Interactive Filters

Users can dynamically filter the dashboard by:

- Region
- Year
- Product Category
- Price Tier

This allows users to investigate sales performance across different business dimensions.
---

## 2. Key Influencers – Profitability Analysis

The Key Influencers page uses Power BI's **Key Influencers visual** to investigate the factors associated with changes in Total Profit.

The analysis identifies factors such as:

- Price Tier
- Product Category
- Order Size
- Discount Amount

For example, the analysis indicates that higher-priced products are associated with a higher average Total Profit.

This page helps move the analysis beyond descriptive reporting toward understanding **what factors are associated with profitability**.
---

## 3. Decomposition Tree – Hierarchical Sales Analysis

The Decomposition Tree is used to break down Total Sales across multiple dimensions.

The analysis can explore sales hierarchically by:

**Region → Product Category → Price Tier → Order Size → Product**

This allows users to drill down from overall sales into increasingly detailed levels and identify the segments and products contributing to sales performance.
---

## 4. Market Share & Distribution

A Treemap visualization is used to analyze the distribution of sales across regions.

The visualization makes it easy to compare the relative contribution of each region to total sales.

### Highest Sales Regions

Some of the strongest regions include:

- Southwest
- Canada
- Northwest
- Central
- Southeast
- Northeast

This provides a quick view of the geographical distribution of sales.
---

# 🔍 Key Insights

Based on the dashboard analysis:

### 💰 Sales & Profitability

- Total Sales reached **138.41M**.
- Total Profit reached **55.61M**.
- The overall Profit Margin is approximately **40.17%**.
- Total Orders reached approximately **215K**.

### 🚲 Product Categories

**Bikes** are by far the largest contributor to sales, generating approximately **115M**, significantly more than Components, Clothing, and Accessories.

### 💵 Price Tiers

Products priced **over $1,500** generate the highest sales contribution and also show the highest average profit in the Key Influencers analysis.

### 📦 Order Size

Small orders (2–5 items) represent the largest share of sales, followed by medium orders (6–15 items).

### 🌎 Regional Performance

The **Southwest** region is the strongest sales contributor, followed by Canada and Northwest.

### 📈 Sales Trend

Sales and profit show noticeable changes over time, with performance increasing significantly through the earlier years before experiencing fluctuations toward the end of the analyzed period.
---
# 📁 Repository Structure

```text
Sales-Insights-Dashboard/
│
├── Images/
│   ├── Sales Overview.jpeg
│   ├── Key Influencer.jpeg
│   ├── Decomposition Tree.jpeg
│   └── Tree Map.jpeg
│
├── Raw Data/
│   └── Raw sales data
│
├── Sales Overview.pbix
│
└── README.md
