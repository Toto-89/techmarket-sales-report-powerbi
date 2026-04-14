# TechMarket Sales Report in Power BI

## Project overview
This project was developed for **TechMarket S.p.A.**, a leading Italian electronics retail chain with stores distributed across the country.  
The goal was to design an interactive Power BI report capable of transforming large volumes of sales data into clear, navigable, and decision-oriented insights.

## Business context
TechMarket needed a reporting system to help managers and decision-makers:
- monitor monthly sales performance
- analyze sales by city and by product
- evaluate the effectiveness of discounts and promotions
- understand the performance of each store
- calculate net sales by considering returned transactions

The project was designed to improve visibility over retail performance and support faster, data-driven decisions.

## Project objectives
The report was built to:
- visualize monthly sales considering **units sold**, **unit price**, and **discount**
- analyze sales across different cities
- monitor product-level performance
- provide a complete overview of each store
- integrate return data to calculate **net sales**
- improve usability through interactive report navigation

## Files included
- **Progetto Gestione Vendite.pbix** → final Power BI report file
- **Dati-20260414T084531Z-3-001.zip** → sales source files
- **Dati negozi-20260414T084545Z-3-001.zip** → store, product, and province source files
- **Resi-20260414T084558Z-3-001.zip** → returns source files

## Data sources
The project integrates multiple datasets:
- **sales data** from TechMarket stores for different months of 2014
- **store data**
- **product data**
- **Italian provinces data**
- **returns data**

These data sources were combined to build a complete model for sales and performance reporting.

## Data transformation
The data preparation phase included:
- loading files from multiple folders
- combining monthly sales files
- merging sales data with product and store information
- enriching the model with product descriptions and unit prices
- integrating return data for net sales analysis

Main Power Query operations:
- append
- merge
- expand
- column transformation
- data cleaning and restructuring

## Report structure

### 1. Monthly Sales
This page shows total sales by month, taking into account:
- **units sold**
- **unit price**
- **discount**

Purpose:
- track monthly business performance
- identify stronger and weaker periods
- evaluate the impact of discounts on sales

### 2. Units Sold by City
This page analyzes the quantity of products sold across cities where TechMarket stores are located.

Purpose:
- compare sales distribution geographically
- identify the best-performing cities
- support location-based business decisions

### 3. Product Detail
This page focuses on product-level analysis.

Purpose:
- monitor the performance of each product
- compare product sales trends
- identify top-performing products

### 4. Store Information
This page provides a complete overview of each store by combining store master data with sales performance.

Purpose:
- evaluate store-level performance
- support management of local operations
- provide a complete retail view for each point of sale

### 5. Returns and Net Sales
This page includes return data to calculate net sales, excluding returned transactions.

Purpose:
- provide a more realistic representation of performance
- distinguish gross sales from effective net sales
- improve the accuracy of business evaluation

## Interactivity and navigation
The report was designed to be interactive and user-friendly through:
- page navigation buttons
- bookmarks
- multiple report pages for targeted analysis
- visual exploration of sales and return data

## Skills demonstrated
This project showcases the following Power BI skills:
- data loading from multiple files
- Power Query transformation
- data model integration
- merge and append operations
- DAX calculations
- KPI-oriented reporting
- interactive dashboard design
- retail sales analysis
- net sales analysis with returns

## Business value
The project provides value to TechMarket by:
- improving visibility on store and product performance
- supporting data-driven decision-making
- helping optimize promotional strategies
- enabling more accurate sales analysis through return integration
- improving report accessibility for non-technical users

## Tools used
- **Power BI**
- **Power Query**
- **DAX**

## Author
**Salvatore Spagnolo**
