# Regional Sales Analysis (2014-2018)

## 📊 Project Overview

This project presents an in-depth Exploratory Data Analysis (EDA) of Acme Co.'s sales data from 2014 to 2018. The primary goal is to analyze historical sales patterns across various dimensions—products, channels, regions, and customers—to identify key drivers of revenue and profit.

The analysis dives into temporal trends, uncovers top-performing segments, and identifies outliers to provide actionable insights. These findings are then used to inform strategic recommendations aimed at optimizing pricing, promotions, and market expansion for sustainable growth. The project culminates in a set of mockups for a Power BI dashboard designed to empower business users with self-service analytics.

---

## 🎯 Business Problem & Objective

**Problem Statement:**
Acme Co. faces inconsistent revenue and profit performance across its U.S. regions and lacks clear visibility into seasonal trends, top-performing products, and channel profitability.

**Objective:**
To analyze Acme Co.’s 2014–2018 sales data to identify key revenue and profit drivers, uncover seasonal trends and outliers, and align performance against budgets. These insights will be used to optimize pricing, promotions, and market expansion strategies, ultimately guiding the design of an interactive Power BI dashboard.

---

## ⚙️ Project Workflow

The project followed a structured workflow to ensure a comprehensive analysis:
1.  **Define Business Objective:** Understood the core problem and the expected business outcomes.
2.  **Data Collection & Consolidation:** Gathered and understood the schema of multi-sheet Excel data.
3.  **Data Loading & Initial Exploration:** Loaded the dataset into a Jupyter Notebook for initial profiling using Python.
4.  **Data Pre-processing & Cleaning:** Handled nulls, fixed headers, merged tables, formatted dates, and normalized column names for consistency.
5.  **Feature Engineering:** Created new, valuable metrics such as `profit` and `profit_margin_pct` to deepen the analysis.
6.  **Exploratory Data Analysis (EDA):** Performed univariate, bivariate, and temporal analysis to visualize trends, compare performance, and extract key insights.
7.  **Dashboarding & Recommendations:** Designed an interactive Power BI dashboard and formulated strategic recommendations based on the findings.

---

## 🛠️ Tools & Technologies

* **Data Analysis & Wrangling:** Python (Pandas, NumPy)
* **Data Visualization:** Matplotlib, Seaborn, Plotly
* **Dashboarding:** Power BI
* **Environment:** Jupyter Notebook (Google Colab)

---

## 🔍 Key Insights from EDA

The analysis revealed several key patterns and opportunities:

#### 1. **Temporal Trends**
* Sales consistently cycle between **$24M and $26M**, with clear peaks in late spring (May–June) and troughs each January.
* The overall trend is stable year-over-year, but a sharp, anomalous revenue drop occurred in **early 2017**, warranting further investigation.


#### 2. **Product & Channel Performance**
* **Top Products:** **Product 26 ($118M)** and **Product 25 ($110M)** are the clear revenue leaders, driving a significant portion of total sales.
* **Channel Mix:** **Wholesale** is the dominant channel, accounting for **54.1%** of sales, followed by Distributors (31.3%) and Exports (14.6%). Although smaller in volume, the **Export** channel shows the highest average profit margin.


#### 3. **Geographic & Customer Insights**
* **Regional Dominance:** The **West** region leads in sales (~$360M), followed closely by the South and Midwest. The Northeast trails significantly, indicating a market gap.
* **State Performance:** **California** is the top-performing state by a wide margin, generating **$228.8M in revenue** (19.5% of total).
* **Customer Segmentation:** A small group of top customers (led by Aibox Company at $12.5M) drives a disproportionate share of revenue, highlighting high customer concentration.

---

## 💡 Recommendations

Based on the analysis, the following strategic actions are recommended:

1.  **Optimize Seasonal Promotions:** Launch recovery campaigns during the April dip and amplify January offers to smooth out seasonal revenue swings.
2.  **Refine Product Strategy:** Double down on marketing for top products (26 & 25) and re-evaluate pricing or phase out low-margin SKUs to improve profitability.
3.  **Expand High-Margin Channels:** Invest in targeted overseas marketing and distributor partnerships to grow the high-margin **Export channel**.
4.  **Target Geographic Growth:** Replicate California's success model in other regions and boost marketing investment in the underperforming **Northeast**.
5.  **Strengthen Customer Relationships:** Prioritize retention and upsell strategies for the top 10 customers while launching targeted campaigns to elevate the lower-revenue cohort.

---

## 🚀 Power BI Dashboard Preview

To make these insights accessible to business users, an interactive Power BI dashboard was designed. It provides a live, filterable view of key performance indicators.

**Page 1: Executive Overview & Trends**
*Provides a high-level summary of KPIs, revenue rhythms, order value distribution, and margin analysis.*

<img width="1007" height="553" alt="Image" src="https://github.com/user-attachments/assets/8ac7064b-b168-4f98-86f7-82ac430efbff" />

**Page 2: Product & Channel Performance**
*Allows for deep dives into product revenue, margin champions, and channel profitability.*

<img width="1010" height="558" alt="Image" src="https://github.com/user-attachments/assets/63a67f80-de31-4a29-bf63-2dd5fbed2347" />

**Page 3: Geographic & Customer Insights**
*Visualizes sales by state, region, and top/bottom customer segments.*

<img width="1003" height="558" alt="Image" src="https://github.com/user-attachments/assets/be7b617d-b437-4309-8f03-a02d33afe9e7" />

---

## 📂 How to Run this Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```

2.  **Run the Notebook:**
    Open and run the `EDA_Regional_Sales_Analysis.ipynb` file in a Jupyter environment.
