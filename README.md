# <img src="https://miro.medium.com/v2/resize:fit:1400/1*8bUjUiCWk0VhS8-lgAj0Og.png" width="4%" height="4%"> Business Insights 360


## Project Overview

AtliQ Hardware, a company specializing in the manufacturing and distribution of computers and peripherals, has experienced rapid growth across various countries. Traditionally, the company relied on Excel files for data analytics. However, this approach proved inadequate for generating actionable insights, leading to significant losses, notably in the Latin American market. Recognizing the need for a more robust analytics solution, senior executives initiated the Business Insights 360 project to implement a comprehensive Power BI dashboard.

To outshine competitors, they've adopted Power BI for analytics with 1.8 million transaction records from Excel, CSV, and MySQL. The Power BI Dashboard includes:
- Home Page: Central navigation for Dashboard.
- Finance: Develop a Profit and Loss statement to evaluate financial performance across different markets, products, and customer segments.
- Sales: Identify top and bottom-performing customers, along with key sales metrics, to enhance customer relationship management.
- Marketing: Analyze product performance metrics to inform marketing strategies and product development.
- Supply Chain: Assess supply chain efficiency through KPIs such as forecast accuracy, net error, and absolute error.
- Executive: Provide an integrated dashboard offering key insights for top-level management people to have effective decision-making.
- Product: Stakeholder's request to view overall market top 5 & bottom 5 products based on GM% Growth YoY and the post discounts % trend for each customer.

---

## [Business Insights 360 Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiZjQwNDU5Y2MtOWFiNC00NGE2LWJkMDYtYzk4Nzg3N2NmMDdhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## [Linkedin Post Engagement](https://www.linkedin.com/posts/prateek27w_bi-360-activity-7287486811235315712-H71g?utm_source=share&utm_medium=member_desktop)

---

## [Video Presentation Link](https://youtu.be/_pZGiNtjtac)

---

## About AtliQ Hardware Company:
**Departments:** Finance, Sales, Marketing, Supply Chain and Executive

- AtliQ Hardwares manufactures and sells computer hardware and peripherals like PC, mouse, printer, USB etc. to different customers across the world.
- Having a major B2B business model wherein they sell hardware to different customers like Croma, Reliance Digital, Amazon, Flipkart etc. who then sell it to the end users (consumers).
- AtliQ operates through 3 channels: Retailer, Direct and Distributor.
- In Retailer Channel they capture two types of platforms:
  1. Brick & Mortar Customer: Actual physical stores e.g. Croma, Best Buy
  2. E-commerce Customer: Online websites E.g. Amazon, Flipkart
- AtliQ Hardwares also has their own stores in the market: AtliQ E-store and AtliQ Exclusive : known as Direct channel.
- In few countries, due to certain government regulations, products can't be sold directly. Instead there's a concept of Distributors, through which the products are distrubuted further. E.g. Neptune

---

### Questions to ask before starting with dashboard

- What is the main objective of building this PowerBI dashboard?
- In what terms the success of this project will be measured?
- Do stakeholders expect the initial pre-view of dashboard before the actual release?
- What hopes & fears does the stakeholders have out of this project?
- Who will be end users using this dashboard and for what purpose?
- What can be go wrong while building this project?
- What are the resources or the data sources needed to build this dashboard?
- Is there any specific inputs from stakeholders in terms of design and views of the dashboard?

After the project kick off meetings, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

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

- **Fact tables** :
    - **Fact sales monthly** : sales values for products.
    - **Fact forecast monthly** : forecast values for products.

- **Excel Files** :
  - market_share: contains market level total sales information about all the competitive players present in the market | 737 records
  - operational_expense: spends made by the comapny for ads & promotions as well as perational cost | 113 records 
  - ns_gm_target: target numbers given by the management team for the current fiscal | 321 records

---

## Data Model:

- Data modeling is the process of structuring and organizing data to create relationships, and establish a framework for effective data analysis and reporting.
- It ensures data accuracy, facilitates complex calculations, and enhances data integration, providing a solid foundation for informed decision-making and business intelligence.
- Here, all the tables are connected by one to many relationship following the Star & Snow-flake Schema Modeling Technique. 

![Image](https://github.com/user-attachments/assets/caa1082c-9aa5-4834-8bdf-b315ddbdb8bf)

---

## Technical Skills:

- [x]	Proficiency in performing ETL (Extract, Transform, Load) process.
- [x]	Creating a seperate date table covering minimum and maximum date ranges given in the dataset using Power Query.
- [x]	Ability to interpret & extract fiscal year from the given data and deriving fiscal months & quarters respectively.
- [x]	Establishing data model relationships among tables with one to many cardinality, following star & snow-flake schema.
- [x]	Proficiency in incorporating supplementary data efficiently into the existing data model & ensuring it functions properly.
- [x]	Utilizing DAX formulas & calculations to create appropriate measures & calculated columns, alongwith utilizing different options like field parameter, bookmark, tool-tip, slicers, page-level filters etc in Power BI.
- [X] Ensuring there is no performance issues like report loading time, increased file size, slow data refresh etc.	

---

## BI 360 Report Overview:

### I. Home View:

A source page providing easy page navigation access to all views, with dedicated support pane and information manual.

![Home View.gif](https://github.com/prateek27w/Business-Insights-360/blob/main/Dashboard%20Navigation/HOME.gif)

### II. Finance View:

Enhances financial planning and cost control, featuring a Financial P&L (Profit & Loss) Statement, Net Sales Trend and Breakdown by Products/Customers and more.

![Finance View.gif](https://github.com/prateek27w/Business-Insights-360/blob/main/Dashboard%20Navigation/Finance.gif)

### III. Sales View:

Focuses on boosting sales revenue and tracking customer performance, including Gross Margin % Variance across Customers/Products and more.

![Sales View.gif](https://github.com/prateek27w/Business-Insights-360/blob/main/Dashboard%20Navigation/Sales.gif)

### IV. Marketing View:

Elevates brand visibility and evaluates marketing campaign ROI, with insights into Segment Performance, Net Profit % Variance across Regions and more.

![Marketing View.gif](https://github.com/prateek27w/Business-Insights-360/blob/main/Dashboard%20Navigation/Marketing.gif)

### V. Supply Chain View:

Optimizes inventory management and demand forecasting, featuring trends in Forecast Accuracy and Inventory Stock Risk by Customers/Products.

![SupplyChain.gif](https://github.com/prateek27w/Business-Insights-360/blob/main/Dashboard%20Navigation/SupplyChain.gif)

### VI. Executive View:

Provides a high-level overview of organizational performance for top AtliQ executives and senior management, showcasing business KPIs, Revenue Contributions by Division/Channel, Top Customers & Products, AtliQ's Market Share Trend and more.

![Executive View.gif](https://github.com/prateek27w/Business-Insights-360/blob/main/Dashboard%20Navigation/Executive.gif)

### VII. Product View:

Stakeholder's request to know the top 5 and bottom 5 products based on GM% Growth YoY and the post discounts % trend in tool-tip for each customer.

![Product View.gif](https://github.com/prateek27w/Business-Insights-360/blob/main/Dashboard%20Navigation/Product.gif)
