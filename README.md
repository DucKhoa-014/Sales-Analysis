# Sales Analysis

![Power BI](https://img.shields.io/badge/Tools-Power%20BI-yellow?style=for-the-badge&logo=powerbi)
![Data Analysis](https://img.shields.io/badge/Domain-Sales%20%26%20Retail-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-green?style=for-the-badge)

---

## 📌 1. Project Overview

This project focuses on analyzing the sales data of a retail business with 18 mixed product categories (phones, electronic devices, games, books, computers, etc.) selling through multiple channels. The dataset covers a 3-year period, spanning from January 1st, 2016 to December 31st, 2018.

The business operates an omnichannel sales model consisting of:
*   **Online Channels:** Telephone, website, email, fax, etc.
*   **Offline Channel:** Local store.

### 🎯 Requirements & Objectives
The objective is to build approximately 8 dashboard pages to evaluate the general overview, conduct deep-dive analysis, and identify opportunities for business improvement. Power BI is the designated tool for this project.

---

## 📊 2. Key Metrics & Analysis Focus

The project measures and evaluates performance based on the following key metrics and core analysis areas:
*   **Revenue:** Total sales value generated.
*   **Quantity:** Total volume of products sold.
*   **Average selling price:** The fluctuation of product pricing.
*   **Gross profit:** Sales revenue minus cost of goods sold.
*   **Gross profit margin:** Profitability percentage on revenue.
*   **Number of orders:** Total volume of successful transactions.
*   **Product performance:** Evaluating how different items contribute to the business.
*   **Sales channel performance:** Analyzing the efficiency of each distribution channel.

### 🔍 Core Business Questions to Answer
The interactive dashboards are designed to comprehensively answer the following questions:
*   Where does product revenue come from?
*   What are the revenue trends over time?
*   How does revenue compare across different sales channels?
*   Which products achieve the best or worst performance in terms of revenue, quantity sold, and gross profit?

---

## 🛠️ 3. Step-by-Step Process

The deployment of the reporting system follows a standard data analytics lifecycle:

### Step 1: Business Understanding
*   Studied the omnichannel retail sales requirements based on the provided business problem description.
*   Defined the core objectives and outlined the main business questions that need to be addressed by the dashboards.

### Step 2: Data Acquisition & ETL (Data Cleansing)
*   Imported 3 years of operational retail data (2016 - 2018) into Power BI.
*   Used Power Query to clean data, handle missing values (Nulls), remove duplicates, and standardize formats across the 18 product categories and channels.

### Step 3: Data Modeling
*   Designed a Star Schema model to optimize data query performance inside Power BI.
*   Established structured relationships (1:N) between the core transactional table (Fact Sales) and descriptive lookup tables (Dim Products, Dim Channels, Dim Date).

### Step 4: DAX Measures Development
*   Developed DAX formulas to accurately calculate foundational metrics, including Revenue, Quantity, Average selling price, Gross profit, Gross profit margin, and Number of orders.
*   Created Time Intelligence measures to evaluate growth metrics such as Year-over-Year (YoY) and Month-over-Month (MoM) revenue trends over the 3-year timeline.

### Step 5: Dashboard Design & Visualization
Designed and completed approximately 8 dashboard pages in Power BI including:
1.  **Executive Overview:** A high-level summary of the business health including key KPIs and a 3-year performance breakdown.
2.  **Revenue & Trend Analysis:** Tracking revenue changes and seasonal patterns over the 3-year timeline.
3.  **Product Performance Deep-dive:** A deep dive into the 18 mixed items, identifying best-performing and worst-performing categories by revenue, qty sold, and gross profit.
4.  **Profitability Analysis:** Monitoring Gross Profit and Gross Profit Margin to pinpoint cost-saving and optimization opportunities.
5.  **Channel Performance Analysis:** Comparing and evaluating performance between Online channels (telephone, website, email, fax) and Offline channels (local store).
6.  **Geography:** Exploring where revenue originates based on geographical location and major customer profiles.
7.  **Sales Manager Performance**: Comparing manager rankings mirror market size.
8.  **Business Opportunities:** Aggregating critical findings from the data to provide actionable recommendations for business improvement.

### Step 6: Data Analysis & Insights Extraction
*   Utilized interactive cross-filtering and slicers to dissect the core factors contributing to revenue and gross profit.
*   Evaluated performance gaps between sales channels and product lines to identify areas of underperformance.

### Step 7: Actionable Recommendations
*   Formulated data-driven strategies based on dashboard findings to optimize business workflows.
*   Suggested strategic resources allocation for high-ROI sales channels and proposed optimization or pricing plans for low-performing product categories.

---

## 📂 4. Project Directory Structure

```text
├── data/                  # Raw and processed datasets
├── outcome/               # Visual captures of the 8 dashboard pages
├── README.md              # Project documentation and guidelines
└── Sales Report           # Insights and recommendation
