
# AIRBNB MARKET ANALYSIS
<a href="https://public.tableau.com/views/AIRBNBTABLEAUPROJECT/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">Click here</a> to see this project Tableu Public platform


## 1. Project Overview

This Tableau-based analysis explores the Airbnb rental market in Seattle, USA, using a comprehensive dataset of 25,531 unique values. The project's goal is to provide actionable insights for hosts, investors, and platform operators in this competitive short-term rental landscape.
This market analysis demonstrates the power of data-driven decision-making in the dynamic short-term rental industry, offering valuable insights to navigate Seattle's Airbnb ecosystem effectively.

### Key Questions to Answer:

1. **Market Segmentation**
   - How do different types of listings perform in various neighborhoods?
   - Can we segment the market based on price, location, and property features?

2. **Pricing Strategies**
   - Can we identify optimal price points for different types of properties?
   - Which property will have a faster return on investment?

3. **Seasonal Trends**
   - Are there noticeable patterns in booking rates or pricing throughout the year?

4. **Competitive Analysis**
   - Can we identify market gaps or oversaturated areas?

5. **User Acquisition, Retention, and Behavior**
   - Can we identify patterns in listing characteristics that lead to repeat bookings?
   - What features or amenities are most common in highly-rated listings?

6. **Geospatial Analysis**
   - Can we create maps to visualize high-demand areas?

## 2. Dataset Description

- **Data Source**: Airbnb Open Data
- **Number of Listings**: 25,531

## 3. Methodology

### Data Preparation:
- Initial data cleaning using Excel
- Removed duplicates, standardized values, handled missing values and removed outliers 

### Analysis Approach:
- Conducted initial data exploration using Excel's pivot tables and charts
- Identified key variables for further analysis: price, location, property type, number of bedrooms, booking rates
- Created a data model in Tableau by joining relevant tables
- Developed interactive dashboards for each research question
- Applied Tableau's built-in statistical tools, including trend lines
- Utilized Tableau's mapping capabilities for geospatial analysis

### Analytical Techniques :
- Time Series Analysis: Used to identify seasonal trends in booking rates
- Correlation Analysis: Examined relationships between variables
- Clustering: Applied Tableau's built-in clustering feature to segment properties based on features and performance
- Geospatial Analysis: Created maps to visualize high-demand areas

### Validation:
- Cross-validated findings using different subsets of the data
- Conducted sensitivity analysis on key parameters
- Compared results with publicly available Airbnb statistics for Seattle,to check whether my findings align with broader market trends.

## 4. Visualizations and Insights

### 4.1 Revenue per Year
- **Visualization**: Line graph showing booking rates per week of the year to identify seasonal trends in booking demand.
- **Insight**: June and December have the highest booking rates showing potential for dynamic pricing strategies during these high-demand periods. Although, lower booking months, show opportunities for promotional offers.

### 4.2 Average Price by Type of Property
- **Visualization**: Bar chart comparing average nightly price across property type to understand pricing variations based on property features.
- **Insight**: Six-bedroom properties have the highest average price per night command the highest average price per night. It shows potential implications for investors considering property types for purchase.

### 4.3 Revenue by Property Feature
- **Visualization**: Bubble chart illustrating the registered revenue for properties with 1 to 6 bedrooms to compare profitability across different property sizes.
- **Insight**: Despite higher pricing, 6-bedroom properties are not the most profitable. It suggests a sweet spot in the market for 2 to 4 bedrooms.

### 4.4 Price Range per Zipcode
- **Visualization**: Interactive map of Seattle showing price distibution to identify high-value and budget-friendly areas.
- **Insight**: Approximately 11% of the zipcodes have pricing over $160 per night, showing potential for targeted marketing strategies based on location.

### 4.5 Top 10 Most Profitable Neighborhoods
- **Visualization**: Horizontal bar chart ranking neighborhoods by total revenue to highlight the most lucrative areas for Airbnb hosts.
- **Insight**: Queen Anne leads with the highest average prices and total revenue exceeding $12.155M per year bringing insights for property investors on where to focus their efforts.

### 4.6 Distinct Count of Listings by Bedrooms
- **Visualization**: Text table showing the distribution of listings by bedroom count to bring understanding of the competitive landscape and market saturation.
- **Insight**: Approximately 70% of the listings are for 1-bedroom properties indentifying potencial gaps in the market. Highlights implications for hosts considering entering the market or expanding their portfolio.

## 5. Implications for Stakeholders

*For Hosts and Property Investors:*
- Consider investing in properties in high-performing neighborhoods like Queen Anne.
- Explore opportunities in under-represented property types to differentiate from the saturated one-bedroom market.
- Implement dynamic pricing strategies to capitalize on seasonal demand fluctuations.

*For Airbnb and Similar Platforms:*
- Develop tools to help hosts optimize pricing based on seasonal trends and local market conditions.
- Consider targeted marketing to attract more diverse property types to the platform.

## 6. Conclusions
This analysis of Seattle's Airbnb market reveals a dynamic and diverse short-term rental ecosystem. The insights gained demonstrate the power of data-driven decision-making in the hospitality industry. By leveraging these findings, stakeholders can make more informed decisions, whether they're hosts looking to optimize their listings, investors seeking profitable opportunities, or platforms aiming to improve their services.

As the short-term rental market continues to evolve, ongoing analysis will be crucial to stay ahead of trends and maintain a competitive edge. This project serves as a foundation for understanding the current state of Seattle's Airbnb market and provides a roadmap for future investigations to further unlock the potential of this vibrant sector.

## 7. Future Research Directions

1. Deep Dive into High-Performing Areas: Conduct a detailed analysis of top-performing neighborhoods to identify common success factors.

2. Guest Satisfaction Analysis: Correlate property features and pricing with guest ratings to identify key drivers of guest satisfaction.

3. Long-Term Market Trends: Extend the analysis over multiple years to identify long-term shifts in the Seattle Airbnb market.

4. Competitive Landscape: Compare Airbnb data with traditional hotel performance in Seattle to understand the broader accommodation market.

5. Economic Impact Study: Assess the economic impact of Airbnb on Seattle's tourism industry and local economy.
