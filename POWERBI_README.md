Supply Chain Analytics Dashboard — Power BI (V1)

Overview
A Power BI dashboard analysing supply chain performance across three product categories being skincare, haircare, and cosmetics. The report covers sales performance, inventory health, and supply risk across 100 product records.
This is Version 1 of an ongoing dashboard project. V2 will introduce slicers, drill-through pages, conditional formatting, and DAX measures to demonstrate progression in Power BI capability.

Dashboard Pages
Page 1 — Sales Overview

KPIs: Total Revenue · Total Units Sold · Average Price
Visuals:

Revenue by Product Type — horizontal bar chart showing skincare as the highest revenue category
Revenue by Customer Demographics — donut chart breaking down revenue across Female, Male, Non-binary, and Unknown segments

Key Insight: Skincare leads revenue despite carrying the lowest average stock levels — flagging a potential supply risk if demand increases.

Page 2 — Inventory & Supply Risk

KPIs: Average Stock Level · Average Lead Time (Days) · Average Availability
Visuals:

Stock Levels by Product Type — column chart showing cosmetics carrying the highest average stock, skincare the lowest
Order Quantity vs Lead Time by Product Type — scatter chart showing no strong correlation between lead time and order quantity, indicating inconsistent ordering behaviour across the supply chain

Key Insight: The scatter chart shows no consistent ordering pattern as lead times increase — suggesting supplier management and ordering strategy could be optimised for efficiency.

Business Questions Answered
QuestionVisualWhich product category generates the most revenue?Revenue by Product TypeHow is revenue distributed across customer segments?Revenue by Customer DemographicsWhich product type carries the most/least stock?Stock Levels by Product TypeDoes lead time influence how much is ordered?Order Quantity vs Lead Time Scatter

Dataset
FieldDescriptionProduct typeCategory (skincare, haircare, cosmetics)SKUStock keeping unit identifierPriceUnit selling priceAvailabilityStock availability indicatorNumber of products soldUnits sold per SKURevenue generatedTotal revenue per SKUCustomer demographicsBuyer segment (Female, Male, Non-binary, Unknown)Stock levelsCurrent inventory levelsLead timesSupplier lead time in daysOrder quantitiesUnits ordered per transaction
Source: Kaggle Supply Chain Dataset (100 records)

What's Coming in V2

Slicers — filter by product type, supplier, and transportation mode
Drill-through pages — click a product to see its full detail
Conditional formatting — red/amber/green KPI indicators
DAX measures — Month-on-Month growth, % of total revenue, stock turnover rate
Logistics page — shipping cost, carrier performance, and route analysis


Tech Stack
PowerBI
Microsoft Excel

Skills Demonstrated

- Building a multi-page Power BI report from a raw CSV dataset
- Data type correction and column transformation in Power BI
- KPI card design and chart selection for business reporting
- Interpreting supply chain metrics and surfacing actionable insights
- Clean, consistent dashboard layout and visual design


Built by ** Modiehi Mphuthi**
