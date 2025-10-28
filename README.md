#Real Estate Analytics Dashboard (Power BI)

This dashboard provides a visual overview of the real estate market with insights on property distribution, pricing trends, and location-based listings. It helps users quickly understand which property types and locations are performing better in terms of pricing and availability.

 Key Features

| Feature | Description |
| KPIs Summary | Shows Total Listings, Total Area (sqft), Average Price, and Avg Price per Sqft |
| Interactive Filters | Users can filter by Date, Location, and Bedrooms |
| Property Type Distribution | Donut chart to show property categories like Apartments, Villas, etc. |
| Price Trend Over Time | Bar/Column chart showing price variation |
| Listing by Location Category | Comparison of Urban vs Other city listings |

Tools Used

| Tool | Purpose |
| Power BI | Dashboard Design and Visualization |
| Excel / CSV | Data Source |
| DAX | Used for basic KPIs and measures |

| Column Name | Description |
| Date | Posting / Listing Date |
| Location | City Name |
| Property_Type | Type of Property (Apartment/Villa/etc.) |
| Area_sqft | Area in Square Feet |
| Price | Total Price |
| Bedrooms | No. of Bedrooms |
| Location_Category | Urban or Other city |

KPIs Calculated

| KPI Name | Formula |
| Total Listings | COUNT(Property_ID) (or total rows) |
| Total Area (sqft) | SUM(Area_sqft) |
| Average Price | AVERAGE(Price) |
| Avg Price per Sqft | Price / Area_sqft |

 Insights Observed

- Apartments are the most frequently listed property type.
- Urban cities have more listings compared to other locations.
- Average price per sqft varies mainly based on location.
- Bedroom count affects pricing trend across filtered areas.

How to Use the Dashboard

1. Select *Date* to view listings of a specific period.
2. Filter by *Location* to see city-wise performance.
3. Filter by *Bedrooms* to compare 2BHK vs 3BHK properties.
4. Hover on charts to see tooltips for more details.
5. Use KPI cards to quickly understand market condition.


Future Enhancements

- Add trendline for price movement over different time periods.
- Include revenue forecast using basic predictive analytics.
- Add tooltip pages for detailed drilldown views.
- Add map visualization for better geo-analysis.


Author

*Name:* Afsana  
*Role:* Data Analyst (Fresher)  
*Tools:* Power BI • Excel • SQL • Python (Pandas)

