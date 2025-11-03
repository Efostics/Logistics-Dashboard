# LOGISTICS PERFORMANCE ANALYSIS

<a href="https://app.powerbi.com/groups/me/reports/274e63d8-506b-4990-b6f7-7a79710137fc?experience=power-bi" target="_blank">
  <img width="2000" height="2000" alt="Blank 2 Grids Collage" src="https://github.com/user-attachments/assets/4e613845-70bb-4f22-a069-6abeb36a6e77" />
</a>


### Introduction
This project centers on analyzing logistics performance for a transportation firm to optimize supply chain operations, reduce costs, and enhance delivery reliability. With increasing competition, fluctuating fuel prices, and customer demands for faster service, understanding shipment patterns is essential for maintaining business sustainability and competitiveness.

### Problem Statement
The firm faces challenges with rising costs, delays, and underperforming routes, prompting the question:
- "Why are our logistics operations facing inefficiencies and delays?"

This analysis addresses this issue by answering key questions:
- What are the performance metrics (transit time, cost, on-time rate) by carrier, warehouse, and route?
- How do cost, weight, distance, and transit days correlate, and are there cost outliers?
- Which carriers or routes have the highest delay rates?
- Which warehouses handle the most volume, and where can new hubs improve efficiency?

The goal is to identify patterns and recommend strategies to improve efficiency and retention.

### Methodology
Step 1: Data Cleaning and Transformation

Tools: Power Query (Power BI)
- Removed duplicates to ensure data integrity.
- Standardized carrier names (e.g., Amazon Logistics, FedEx) and warehouse identifiers.
- Transformed Shipment_Date into a Date table for time-based analysis.
- Calculated Transit_Days where missing using DATEDIFF(Shipment_Date, Delivery_Date, DAY).

Step 2: Analysis and Dashboard Design

Tools: PowerPoint, Power BI visualization features
- Developed a wireframe in PowerPoint to plan layout, prioritizing KPI cards, charts, and slicers.
- Built a two-page dashboard in Power BI:
- Implemented slicers for Date Range,  Origin_Warehouse, and Destination to enable interactive filtering.
- Utilized DAX measures (e.g., Average Transit Time, On-Time Delivery Rate, Delay Rate) to aggregate and format data.
- Applied visualizations: Bar charts, scatter plots, line charts, and tables to highlight trends and correlations.

### Insights
- Total Metrics: 2,000 shipments. 4-day average transit time. 82.40% on-time delivery rate, this is good, but room for improvement. 9.95% delay rate (compromises customer satisfaction), and $205 average cost per shipment.
- Carrier Performance: LaserShip leads with 4.04 days transit, FedEx highest cost at $64K .
- Monthly Trends: August peaks at $46K cost and 182 shipments, declining through December.
- Cost vs. Weight: DHL and UPS charge excessively for low weight, FedEx and lasership has good cost but slower.
- Warehouse Insights: NYC has highest on-time delivery at 88.82%, MIA has lowest at 78.11% (indicates operational gaps).

### Recommendations
- Investigate Amazon (12.41%) and DHL (13.88%) delay causes to boost on-time rates and reliability.
- Explore cost optimization with DHL and UPS to reduce budget strain from high charges.
- Analyze August spike drivers to better align resources with seasonal demand.

