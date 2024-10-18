# British Airways Customer Feedback Analysis

**Author: Namratha**

<img width="1197" alt="britishairways" src="https://github.com/user-attachments/assets/4295f861-fb8f-42c5-9226-657a2d28b6be">

## Overview

This analysis of British Airways customer feedback from **2016 to 2023** provides key insights into overall customer satisfaction and identifies critical areas for improvement. With an average overall rating of **4.2/6**, the data highlights both strengths and significant weaknesses, offering opportunities for actionable improvements that can drive business value.

---

## Key Business Metrics & Insights

### 1. Overall Customer Satisfaction

- **Average Overall Rating**: 4.2/6

#### Key Weaknesses:
- **Entertainment**: 1.3/6
- **Food and Beverages**: 2.3/6
- **Seat Comfort**: 2.9/6
- **Value for Money**: 2.7/6

#### Strengths:
- **Cabin Staff Service**: 3.3/6
- **Ground Service**: 3.1/6

#### Actionable Insights:
- **Entertainment System Overhaul**: Invest in modern entertainment options (streaming, mobile compatibility).
- **Food and Beverage Revamp**: Partner with popular food brands or regional chefs to improve menu offerings.
- **Seat Comfort Enhancements**: Upgrade seating to improve ergonomics, especially on long-haul flights.

---

### 2. Performance by Aircraft Type

- **Highest-Rated Aircraft**: Boeing 747-400 (5.2/6)
- **Lowest-Rated Aircraft**: Boeing 777-200 (3.4/6) with the highest number of reviews (191).

#### Actionable Insights:
- **Targeted Fleet Investments**: Prioritize service upgrades on underperforming aircraft like the Boeing 777-200 and A321.
- **Optimize Scheduling**: Deploy aircraft with higher satisfaction ratings on high-traffic routes.

---

### 3. Regional Review Trends

Customer satisfaction varies significantly by region, with **Western Europe** and **North America** being the primary review sources.

#### Actionable Insights:
- **Region-Specific Customizations**: Tailor in-flight services based on regional preferences (e.g., food, entertainment).
- **Targeted Marketing Campaigns**: Promote higher-rated routes in key regions to enhance customer perception.

---

### 4. Seasonality & Rating Fluctuations

Satisfaction fluctuates seasonally, with visible dips during peak travel periods.

#### Actionable Insights:
- **Seasonal Staffing & Service Adjustments**: Improve staffing and service quality during high-demand travel periods.
- **Proactive Communication**: Anticipate operational challenges during peak times to mitigate negative feedback.

---

## Strategic Recommendations

1. **Improve In-Flight Experience**: Focus on upgrading entertainment, food, and seat comfort to address critical weaknesses.
2. **Fleet Optimization**: Prioritize upgrades for aircraft models with the most customer feedback (Boeing 777-200, A321).
3. **Enhance Regional Services**: Tailor offerings based on regional preferences to boost satisfaction in key markets.
4. **Boost Value for Money**: Offer bundled deals to enhance perceived value.
5. **Monitor & Adjust for Seasonal Trends**: Use data-driven strategies to manage high-traffic periods and mitigate seasonal dissatisfaction.

---

## Conclusion

By targeting underperforming areas such as in-flight entertainment, food services, and seat comfort, British Airways can significantly improve its overall customer ratings and strengthen its competitive position in the global market.

---

## Dashboard Creation Summary

### Data Sources
- **ba_reviews.csv**: Contains detailed customer reviews, including ratings for various service aspects like cabin staff, entertainment, food, and seat comfort.
- **countries.csv**: Provides country details, enabling geographic analysis of customer reviews.
- These two data sources were **joined on the "countries" field** to link the reviews to their respective regions.

### Key Visual Components
1. **Key Performance Indicators (KPIs)**:
   - Displays average ratings for key categories like Overall Satisfaction, Entertainment, Food, and Cabin Staff Service.
   
2. **Trend Analysis (Line Chart)**:
   - A line chart tracks the trend of average overall rating over time, highlighting fluctuations in customer satisfaction.

3. **Geographic Analysis (Map)**:
   - A map shows customer satisfaction by country, enabling a regional comparison of feedback.

4. **Aircraft Performance (Bar Charts)**:
   - Bar charts compare average ratings and number of reviews for various aircraft types, identifying which aircraft models receive the best and worst reviews.

### Filters
The dashboard includes filters for:
- **Month of review**
- **Seat type** (Business, Economy, First Class)
- **Traveller type** (Family Leisure, Business, etc.)
- **Aircraft type**

These filters provide users the ability to customize the view and explore the data in greater detail.

### Data Source Integration
- The reviews dataset and countries dataset were joined based on the **"countries"** field. This allowed for geographic analysis and the visualization of country-specific feedback.

### Interactivity & Insights
- The dashboard is interactive, allowing users to drill down into specific time periods, aircraft types, traveller types, and more.
- Insights from the dashboard can be used to guide **service improvements**, optimize **aircraft deployment**, and **tailor regional services**.

## Acknowledgments

Thanks to **Mo Chen** for the ideas from his GitHub project that inspired this analysis.
