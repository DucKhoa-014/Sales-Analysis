# Sales Analysis
## Program: STARTTRAIN - THE NEXT ANALYST

![Power BI](https://img.shields.io/badge/Tools-Power%20BI-yellow?style=for-the-badge&logo=powerbi)
![Data Analysis](https://img.shields.io/badge/Domain-Sales%20%26%20Retail-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)

---

## 📌 1. Project Overview

This project focuses on analyzing the sales data of a retail business with 18 mixed product categories (phones, electronic devices, games, books, computers, etc.) selling through multiple channels[cite: 1]. The dataset covers a 3-year period, spanning from January 1st, 2016 to December 31st, 2018[cite: 1].

The business operates an omnichannel sales model consisting of[cite: 1]:
*   **Online Channels:** Telephone, website, email, fax, etc[cite: 1].
*   **Offline Channel:** Local store[cite: 1].

### 🎯 Requirements & Objectives
The objective is to build approximately 8 dashboard pages to evaluate the general overview, conduct deep-dive analysis, and identify opportunities for business improvement[cite: 1]. Power BI is the designated tool for this project[cite: 1].

---

## 📊 2. Key Metrics & Analysis Focus

The project measures and evaluates performance based on the following key metrics and core analysis areas[cite: 1]:
*   **Revenue:** Total sales value generated[cite: 1].
*   **Quantity:** Total volume of products sold[cite: 1].
*   **Average selling price:** The fluctuation of product pricing[cite: 1].
*   **Gross profit:** Sales revenue minus cost of goods sold[cite: 1].
*   **Gross profit margin:** Profitability percentage on revenue[cite: 1].
*   **Number of orders:** Total volume of successful transactions[cite: 1].
*   **Product performance:** Evaluating how different items contribute to the business[cite: 1].
*   **Sales channel performance:** Analyzing the efficiency of each distribution channel[cite: 1].

### 🔍 Core Business Questions to Answer
The interactive dashboards are designed to comprehensively answer the following questions[cite: 1]:
*   Where does product revenue come from?[cite: 1]
*   What are the revenue trends over time?[cite: 1]
*   How does revenue compare across different sales channels?[cite: 1]
*   Which products achieve the best or worst performance in terms of revenue, quantity sold, and gross profit?[cite: 1]

---

## 🛠️ 3. Step-by-Step Process

The deployment of the reporting system follows a standard data analytics lifecycle:

### Step 1: Business Understanding
*   Studied the omnichannel retail sales requirements based on the provided business problem description[cite: 1].
*   Defined the core objectives and outlined the main business questions that need to be addressed by the dashboards[cite: 1].

### Step 2: Data Acquisition & ETL (Data Cleansing)
*   Imported 3 years of operational retail data (2016 - 2018) into Power BI[cite: 1].
*   Used Power Query to clean data, handle missing values (Nulls), remove duplicates, and standardize formats across the 18 product categories and channels[cite: 1].

### Step 3: Data Modeling
*   Designed a Star Schema model to optimize data query performance inside Power BI.
*   Established structured relationships (1:N) between the core transactional table (Fact Sales) and descriptive lookup tables (Dim Products, Dim Channels, Dim Date).

### Step 4: DAX Measures Development
*   Developed DAX formulas to accurately calculate foundational metrics, including Revenue, Quantity, Average selling price, Gross profit, Gross profit margin, and Number of orders[cite: 1].
*   Created Time Intelligence measures to evaluate growth metrics such as Year-over-Year (YoY) and Month-over-Month (MoM) revenue trends over the 3-year timeline[cite: 1].

### Step 5: Dashboard Design & Visualization
Designed and completed approximately 8 dashboard pages in Power BI including[cite: 1]:
1.  **Executive Overview:** A high-level summary of the business health including key KPIs and a 3-year performance breakdown[cite: 1].
2.  **Revenue & Trend Analysis:** Tracking revenue changes and seasonal patterns over the 3-year timeline[cite: 1].
3.  **Product Performance Deep-dive:** A deep dive into the 18 mixed items, identifying best-performing and worst-performing categories by revenue, qty sold, and gross profit[cite: 1].
4.  **Channel Performance Analysis:** Comparing and evaluating performance between Online channels (telephone, website, email, fax) and Offline channels (local store)[cite: 1].
5.  **Profitability Analysis:** Monitoring Gross Profit and Gross Profit Margin to pinpoint cost-saving and optimization opportunities[cite: 1].
6.  **Order & Transaction Insights:** Investigating consumer shopping behaviors through the Number of Orders and cart sizing[cite: 1].
7.  **Regional/Customer Analysis:** Exploring where revenue originates based on geographical location and major customer profiles.
8.  **Business Opportunities:** Aggregating critical findings from the data to provide actionable recommendations for business improvement[cite: 1].

### Step 6: Data Analysis & Insights Extraction
*   Utilized interactive cross-filtering and slicers to dissect the core factors contributing to revenue and gross profit[cite: 1].
*   Evaluated performance gaps between sales channels and product lines to identify areas of underperformance[cite: 1].

### Step 7: Actionable Recommendations
*   Formulated data-driven strategies based on dashboard findings to optimize business workflows[cite: 1].
*   Suggested strategic resources allocation for high-ROI sales channels and proposed optimization or pricing plans for low-performing product categories[cite: 1].

---

## 📂 4. Project Directory Structure

```text
├── data/                  # Raw and processed datasets
├── pbix/                  # Power BI project file (.pbix)
├── screenshots/           # Visual captures of the 8 dashboard pages
└── README.md              # Project documentation and guidelines
