# Coffee-Sales-Dashboard
# Project Overview
This Excel-based Coffee Sales Dashboard transforms raw transactional data into insightful visualizations that support strategic decisions. Built with three source tables (Orders, Products, Customers), the dashboard tracks monthly sales trends, top-performing countries, top 5 customers, roast-type popularity, and purchase size preferences. Interactive slicers (Size, Roast Type, Loyalty Card) and a timeline allow users to slice by period and segment—facilitating detailed drill-down into trends.
# Project Workflow
Data Ingestion & Cleaning: Imported Orders, Products, and Customers tables; removed nulls, standardized date formats and units, and removed duplicates.

Enrichment: Merged datasets using formula-based lookups (XLOOKUP/INDEX-MATCH) to add customer, product, size, roast, and loyalty details.

Preparation: Calculated Sales = Quantity × Unit Price, and derived clear labels for coffee type and roast via IF functions.

Analysis: Created pivot tables for sales over time, sales by country, and spend by customer.

Visualization: Built pivot charts and KPI tiles; added slicers (Size, Roast, Loyalty) and timeline for interactive filtering.

Dashboard Assembly: Laid out charts, slicers, and KPIs on a dedicated sheet for an intuitive user experience.

# Tools & Techniques
1. Microsoft Excel (pivot tables, pivot charts, slicers, timeline)

2. Formulas: XLOOKUP, INDEX-MATCH, IF, and arithmetic calculations for Sales

3. Data Management: Data cleaning (nulls, duplicates, formatting), table conversion, date and unit standardization — techniques widely used in similar Excel dashboards

