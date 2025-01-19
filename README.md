# <img src="https://miro.medium.com/v2/resize:fit:1400/1*8bUjUiCWk0VhS8-lgAj0Og.png" width="4%" height="4%"> Business Insights 360

<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Assets/BI%20360%20Project%20Thumbnail%2BLogo.png" width="100%" height="100%"> </div>

![Image](https://github.com/user-attachments/assets/ab7a9284-1844-44b5-be2c-0bb300c7d3ed)

This repository serves as my documentation for the AtliQ Hardwares Business Insights 360 - Power BI Project.
It was created as a self-learning project for the course: [Get Job Ready: Power BI Data Analytics for All Levels 2.0](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project) by [Codebasics](https://codebasics.io/).

The entire project has been implemented using Microsoft Power BI Desktop 2.128.751.0 and published on Microsoft Power BI Service.

The project data files have not been uploaded to this repository in compliance with Codebasics Data & Content Distribution Policy.

---

## [Business Insights 360 Live Report Link](https://mavenanalytics.io/project/19189)

---

## Introduction to AtliQ Hardware:
**Domain:** Consumer Goods | **Functions:** Finance, Sales, Marketing, Supply Chain and Executive

- AtliQ Hardwares is company that sells computer hardware and peripherals like PC, mouse, printer etc. to clients across the world.
- They have a major B2B business model wherein they sell to stores like Croma, Best Buy, Staples, Flipkart etc. who then sell it to the end users (consumers). These stores are their main customers.
- They sell through 3 channels: Retailer, Direct and Distributor.
- AtliQ Hardwares’s Customers are of two types. Both these Platforms are called Retailer channels.
  1. Brick & Mortar Customer: Actual physical stores e.g. Croma, Best Buy
  2. E-commerce Customer: Online websites E.g. Amazon, Flipkart
- AtliQ Hardwares also has a minor B2C business model wherein they own stores: AtliQ E-store and AtliQ Exclusive. These are called Direct channels.
- They also have Distributors in some countries with restricted trade. E.g. Neptune

## Project Objective:
AltiQ Hardware, a global leader in computers and accessories, faced unexpected losses after opening a store in America. These setbacks were identified to be caused due to reliance on outdated methods such as Excel for data analysis. To address this issue, the company's leadership recognized the need for a transformative approach to leveraging data for informed decision-making. With competitors boasting robust analytics teams, AltiQ Hardware recognizes the urgent need to develop its analytics capabilities using Power BI to thrive in the industry.

To outshine competitors, they've adopted Power BI for analytics with 1.8 million transaction records from Excel, CSV, and MySQL. The Power BI Dashboard includes:
- Home Page: Central navigation for Dashboard.
- Finance: Enhances financial planning.
- Sales: Boosts revenue and market share.
- Marketing: Elevates brand visibility.
- Supply Chain: Optimizes inventory management.
- Executive: Provides top management overview.

## Tools used:
1. Microsoft Power BI: for Data ETL, Data Modelling, Data Visualization & Dashboarding
2. GitHub - for Documentation

## Skills & Methodologies implemented:
1. Data Cleaning: **Power Query**
2. Data Manipulation: **DAX Measures & Columns, Numeric & Field Parameters**
3. Data Modelling
4. Data Visualization: **Conditional Formatting, Custom Tooltip**
5. Dashboarding: **Filters, Custom Icon Buttons, Slicers, Bookmarks, Page Navigation**
6. Report Publishing: **PBI Service and Report Optimization**
7. Documentation

---

## About the Dataset:

### Dataset Includes:

- **Customer dimension table** :
    - **74 customers** with total of **209 stores** spread across **27 markets/countries**.
    - **2 platforms** - Brick and Mortar, and E-Commmerce
    - **3 Channels** - Retailer, Direct, and Distributors.

- **Market dimension table** :
    - **27 markets** spread across **7 sub-zones** in **4 broad regions**, that are : APAC(Asia Pacific), EU(European Union), NA(North America), LATAM(Latin America)

- **Product dimension table** :
    - **3 divisions** : Networking and Storage (N & S), Peripherals and Accessories (P & A), PC.
    - **6 segments** & **14 Categories** of products.

- **Fact tables**
    - **Fact sales monthly** : sales values for products.
    - **Fact forecast monthly** : forecast values for products.
- Excel Files:
  - market_share: 737 records | 6 columns
  - operational_expense: 113 records | 4 columns
  - ns_gm_target: 321 records | 5 columns


---

## Data Model:
<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Data%20Model/Data%20Model%20Final.PNG" width="100%" height="100%"> </div>

---


## BI 360 Report Overview:

### I. Home View:

Central navigation hub with easy access to all views, complete with support and information manual.

<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Power%20BI%20Report/Report%20Images/Business%20Insights%20360%20Report%20-%20Reinvented%20-%20Home%20View.png" width="100%" height="100%"> </div>

### II. Finance View:

Enhances financial planning and cost control, featuring a P&L Statement, Net Sales Trend and Breakdown by Products/Customers and more.

<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Power%20BI%20Report/Report%20Images/Business%20Insights%20360%20Report%20-%20Reinvented%20-%20Finance%20View.png" width="100%" height="100%"> </div>

### III. Sales View:

Focuses on boosting sales revenue and tracking customer performance, including Gross Margin % Variance across Customers/Products and more.

<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Power%20BI%20Report/Report%20Images/Business%20Insights%20360%20Report%20-%20Reinvented%20-%20Sales%20View.png" width="100%" height="100%"> </div>

### IV. Marketing View:

Elevates brand visibility and evaluates marketing campaign ROI, with insights into Segment Performance, Net Profit % Variance across Regions and more.

<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Power%20BI%20Report/Report%20Images/Business%20Insights%20360%20Report%20-%20Reinvented%20-%20Marketing%20View.png" width="100%" height="100%"> </div>

### V. Supply Chain View:

Optimizes inventory management and demand forecasting, featuring trends in Forecast Accuracy and Inventory Stock Risk by Customers/Products.

<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Power%20BI%20Report/Report%20Images/Business%20Insights%20360%20Report%20-%20Reinvented%20-%20Supply%20Chain%20View.png" width="100%" height="100%"> </div>

### VI. Executive View:

Provides a high-level overview of organizational performance for top AtliQ executives and senior management, showcasing business KPIs, Revenue Contributions by Division/Channel, Top Customers & Products, AtliQ's Market Share Trend and more.

<div align="center"> <img src="https://github.com/5ifar/Business_Insights_360/blob/main/Power%20BI%20Report/Report%20Images/Business%20Insights%20360%20Report%20-%20Reinvented%20-%20Executive%20View.png" width="100%" height="100%"> </div>

---

## Conclusion:
The Power BI Report project for AtliQ Hardware provided a comprehensive, data-driven analysis across five critical business functions: Finance, Sales, Marketing, Supply Chain, and Executive. By integrating key business metrics such as Net Sales, Gross Margin, COGS, Net Profit % and Forecast Accuracy % the dashboard offers a holistic view of AtliQ's performance.

The insights gained from this analysis revealed areas of interest, such as robust sales performance and precise forecast accuracy, as well as areas of opportunities for improvement in weak profit margins and supply chain efficiency. Through interactive visualizations and detailed metrics, the dashboard empowers Atliq Hardware's leadership to make informed, strategic decisions that align with their business goals.

---
