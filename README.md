# 🚗 Motor Vehicle Theft Analysis
### An Exploratory and Visual Analysis of Vehicle Theft Patterns Using Power BI

### Project Overview
This project analyzes vehicle theft data to uncover patterns related to time, location, vehicle type, and brand. Using Power BI, I built an executive-style dashboard that
provides actionable insights into theft hotspots, high-risk vehicle categories, and temporal trends to support data-driven decision-making.

### Business Objective
The primary goals of this analysis are to:
* Track vehicle theft trends over time
* Identify high-risk regions and theft hotspots
* Understand vehicle types and brands most targeted
* Analyze theft behavior by day and period
* Support strategic planning for theft prevention and enforcement

### Dataset Description
The dataset consists of three related tables:

1. Stolen Vehicles
* vehicle_id
* vehicle_type
* make_id
* model_year
* vehicle_desc
* color
* date_stolen
* location_id

2. Make Details
* make_id
* make_name
* make_type (Luxury / Standard)

3. Locations
* location_id
* region
* country
* population
* density

### Data Preparation & Modeling

* Loaded and cleaned multiple datasets in Power BI
* Ensured correct data types and relationships
* Built a star schema model for optimal performance
* Created calculated measures for trends and aggregations
* Validated consistency across date, region, and vehicle attributes

[View My Interactive Dashboard Here
](https://app.powerbi.com/view?r=eyJrIjoiMmMwMzU1MGItY2RjYy00NjYyLWI1Y2QtZjc4ZjI2NDMzMTgyIiwidCI6IjE5NDlmNzRjLTQzY2UtNDRhZi1iYTdhLWJhYjRhYjYyNzljNiJ9)
### Key KPIs
* Total Stolen Vehicles
* Top Theft Regions
* Most Stolen Vehicle Type
* Most Stolen Vehicle Make

### Dashboard Visuals

The one-page executive dashboard includes:

1. Theft Trend Over Time (Yearly)
2. Theft Trend by Day of the Week
3. Theft by Region
4. Theft by Vehicle Type
5. Luxury vs Standard Vehicle Theft
6. Theft by Make Name

Visuals use red-accented highlights to emphasize high-theft areas and categories.

### Key Insights
* Vehicle theft is concentrated in specific regions like Auckland, Canterbury, Bay of Plenty,Waikato,Wellington,etc. indicating clear hotspots.
* Certain vehicle types and brands are disproportionately targeted.
* Standard vehicles exhibit different theft patterns compared to Luxury vehicles.
* Theft incidents vary by day of the week, revealing behavioral trends.
* Long-term trends show periods of increased theft requiring proactive intervention.

### Recommendations
* Allocate security and enforcement resources to high-risk regions.
* Encourage enhanced security features for frequently stolen vehicle types.
* Implement region-specific theft prevention strategies.
* Use temporal patterns to optimize surveillance schedules.
* Support insurance and policy decisions with brand-level theft insights.

### Tools & Technologies
* Power BI – Data modeling, DAX, visualization, dashboard design

### Conclusion
This project transforms raw vehicle theft data into a clear, actionable, and executive-ready dashboard, enabling stakeholders to better understand theft risks and design 
effective prevention strategies.
