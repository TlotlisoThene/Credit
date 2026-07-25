# Credit Card Financial Dashboard (Power BI)

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Business Background](#2-business-background)
3. [Business Problem](#3-business-problem)
4. [Business Objectives](#4-business-objectives)
5. [Tools & Technologies](#5-tools--technologies)
6. [Methodology](#6-methodology)
7. [Dashboard](#7-dashboard)
8. [Key Insights](#8-key-insights)
9. [Business Recommendations](#9-business-recommendations)
10. [Challenges & Limitations](#10-challenges--limitations)
11. [Author](#11-author)

---

# 1. Project Overview

This project focuses on developing an interactive **Credit Card Financial Dashboard** using **Power BI** to provide stakeholders with real-time insights into credit card performance. By analyzing customer and transaction data stored in a SQL database, the dashboard enables continuous monitoring of key performance indicators (KPIs), revenue trends, customer behavior, and operational performance.

The dashboard was designed to support data-driven decision-making by transforming raw financial data into meaningful visualizations that help identify trends, evaluate business performance, and uncover opportunities for growth.

---

# 2. Business Background

Financial institutions process millions of credit card transactions every year, making it essential to monitor business performance efficiently. Understanding customer spending behavior, transaction trends, revenue generation, and credit card performance allows businesses to improve customer satisfaction, manage risk, and optimize financial strategies.

An interactive dashboard provides decision-makers with timely insights, enabling them to track performance metrics, identify emerging trends, and make informed business decisions.

---

# 3. Business Problem

The organization required a centralized reporting solution to monitor weekly and yearly credit card performance. Existing reporting methods made it difficult to quickly identify changes in revenue, customer activity, transaction volumes, and card performance.

The business needed an interactive dashboard capable of answering questions such as:

- How is revenue changing over time?
- Which customer groups contribute the most revenue?
- Which credit card types generate the highest transaction volumes?
- Which states contribute the highest revenue?
- How effective are customer activation efforts?
- What is the current delinquency rate?

---

# 4. Business Objectives

The primary objectives of this project are to:

- Develop an interactive dashboard that provides real-time insights into credit card operations.
- Monitor key financial performance indicators, including revenue, interest income, transaction volume, and customer growth.
- Analyze customer demographics to understand revenue contribution across different customer segments.
- Identify the best-performing credit card categories based on transaction activity.
- Track regional performance to identify high-performing markets.
- Monitor customer activation and delinquency rates to support risk management.
- Enable stakeholders to make informed business decisions through interactive data visualizations.

---

# 5. Tools & Technologies

| Tool | Purpose |
|----------|-------------|
| SQL | Data Storage & Data Extraction |
| Power BI | Data Modeling, Dashboard Development & Visualization |
| DAX | KPI Calculations & Measures |
| Power Query | Data Cleaning & Transformation |

---

# 6. Methodology

## 1. Data Preparation

The customer and transaction datasets were imported into Power BI and prepared for analysis.

### Data Cleaning

- Imported customer and transaction data from SQL.
- Checked for missing and inconsistent values.
- Standardized data formats.
- Removed duplicate records where necessary.
- Validated relationships between customer and transaction tables.

### Data Modeling

- Established relationships between transaction and customer tables.
- Created a star schema for efficient reporting.
- Built calculated columns and DAX measures.
- Optimized the data model for dashboard performance.

### KPI Development

Developed measures to monitor key business metrics, including:

- Total Revenue
- Interest Revenue
- Total Transaction Amount
- Total Transaction Count
- Customer Count
- Activation Rate
- Delinquency Rate
- Week-over-Week Revenue Growth

## 2. Dashboard Development

An interactive Power BI dashboard was developed to visualize financial performance and customer behavior.

The dashboard enables stakeholders to:

- Monitor weekly revenue performance.
- Analyze transaction trends.
- Compare revenue across customer demographics.
- Evaluate credit card category performance.
- Monitor state-wise revenue contribution.
- Track customer activation and delinquency rates.
- Filter insights dynamically using interactive slicers.

---

# 7. Dashboard

The dashboard provides an interactive overview of credit card operations through dynamic visualizations and key performance indicators.

### Dashboard Highlights

- Revenue Overview
- Weekly Performance Analysis
- Customer Demographics
- Credit Card Category Performance
- State-wise Revenue Analysis
- Transaction Analysis
- Activation Rate
- Delinquency Rate
- Interactive Filters and Slicers

> **Insert dashboard screenshots here**

---

# 8. Key Insights

The dashboard revealed several important business insights:

- Overall revenue reached **57M**, demonstrating strong financial performance.
- Total transaction amount reached **46M**, while total interest income generated **8M**.
- Revenue increased by **28.8%** during **Week 53**, indicating significant week-over-week growth.
- Male customers generated **31M** in revenue, outperforming female customers, who contributed **26M**.
- **Blue** and **Silver** credit cards accounted for approximately **93%** of all transactions, making them the dominant card categories.
- Customers from **Texas (TX), New York (NY), and California (CA)** contributed approximately **68%** of total revenue.
- The overall customer activation rate reached **57.5%**, indicating that more than half of customers actively use their credit cards.
- The overall delinquency rate remained relatively low at **6.06%**, suggesting healthy credit performance.
- Weekly monitoring enables stakeholders to identify performance changes quickly and respond proactively to emerging business trends.

---

# 9. Business Recommendations

Based on the analysis, the following recommendations were made:

### Increase Customer Activation

Develop targeted marketing campaigns and onboarding incentives to improve customer activation rates.

### Strengthen High-Performing Markets

Focus marketing investments on high-revenue states such as Texas, New York, and California while identifying opportunities to grow lower-performing regions.

### Promote High-Performing Card Categories

Continue promoting Blue and Silver credit cards while exploring strategies to improve adoption of other card categories.

### Improve Customer Retention

Introduce loyalty programs and personalized rewards to encourage repeat usage and increase customer lifetime value.

### Monitor Credit Risk

Closely monitor delinquency trends and implement early intervention strategies for customers at risk of default.

### Track Weekly Performance

Continue monitoring weekly KPIs to quickly identify changes in revenue, transaction activity, and customer behavior, enabling faster business decisions.

---

# 10. Challenges & Limitations

### Challenges

- Integrating customer and transaction data into a single reporting model.
- Creating optimized DAX measures for business KPIs.
- Designing an intuitive dashboard that balances detailed analysis with ease of use.
- Ensuring efficient performance while working with multiple related datasets.

### Limitations

- The dashboard relies on historical transaction data and may not reflect future customer behavior.
- Some business metrics depend on the quality and completeness of the source data.
- External economic conditions and market factors were not included in the analysis.

---

# 11. Author

**Thene Tlotliso**

- 🔗 LinkedIn: [Your LinkedIn URL]
- 💼 Portfolio: https://tlotlisothene.github.io/
- 📧 Email: thenetlotliso@gmail.com

---

*Last updated: July 2026*
