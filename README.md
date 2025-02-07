# British Airways Customer Reviews Dashboard

![British_Airways-Airbus_A321neo_in_flight-640x360-ref180939](https://github.com/user-attachments/assets/deb4f4a1-9eb4-4924-a224-203af2c3941d)


# Project Overview

This project is an interactive data visualization dashboard designed to
analyze British Airways customer reviews. It enables users to explore
customer sentiment, identify trends, and understand key service
performance metrics such as food, entertainment, seat comfort, and staff
service. The dashboard provides insights into service quality by region,
traveler type, and aircraft model, helping stakeholders make data-driven
decisions.

# Problem Statement

The project aims to address key business questions:

- How do different service factors impact customer ratings?

- What regions have the highest and lowest customer satisfaction?

- How has customer sentiment evolved over time?

- Which aircraft models receive the best and worst reviews?

- How do traveler type and seat class influence ratings?

# Data Collection & Preparation

## Data Sources

- [British Airways Reviews Dataset](https://www.kaggle.com/datasets/yaranathakur/british-airways-reviews/data): Contains customer feedback, ratings,
  flight details, and service aspects.

- Country Mapping Dataset: Links customer reviews to geographical
  locations for regional analysis.

## Data Cleaning & Processing

- Addressed missing values and standardized date formats.

- Removed duplicate records to ensure accuracy.

- Categorized aircraft with fewer than 50 reviews into an 'Other'
  category.

# Techniques & Process Followed

Data Importation

- Imported two CSV files (ba_reviews.csv and Countries.csv) into
  Tableau.

- Established a relationship between "place" (in ba_reviews.csv) and
  "country" (in Countries.csv) to enable geographical insights.

Data Relationships

- Linked country mapping table to review data to support filtering by
  region and continent.

- Created calculated fields for custom metrics and parameter-based
  filtering.

Visualization Techniques

- Maps – Showed regional distribution of review ratings.

- Bar Charts – Compared average service ratings across aircraft models.

- Line Graphs – Analyzed trends in customer satisfaction over time.

- Interactive Filters & Parameters – Allowed users to toggle between
  different rating metrics dynamically.

# Key Features & Insights

Dynamic Metric Selection

Users can choose between different review metrics (Overall Rating, Food,
Entertainment, Seat Comfort, Cabin Staff Service, etc.) to analyze
customer sentiment from multiple perspectives.

Geographical Insights

- A color-coded heatmap displays the average ratings per country.

- Clicking on a country filters the entire dashboard to show
  country-specific reviews and trends.

Trend Analysis

- Monthly trend analysis shows how customer satisfaction has changed
  over time.

- Allows users to identify patterns in service improvements or declines.

Customer Segmentation

- Filters allow users to analyze reviews by traveler type, seat class,
  and aircraft model.

- Helps British Airways understand which customer groups have the best
  and worst experiences.

Aircraft Performance Comparison

- A dual bar chart compares average service ratings across aircraft
  models.

- Users can identify which aircraft offer the best or worst customer
  experiences.

# Challenges & Solutions

- Data Gaps: Missing traveler and aircraft details were grouped into
  'Unknown' and 'Various' categories.

- Technical Issues: Used calculated fields to dynamically aggregate
  metrics correctly.

- Performance Optimization: Applied data aggregation techniques to
  enhance dashboard responsiveness.

# Business Recommendations

For British Airways:

- Improve low-rated service factors: Focus on food, entertainment, and
  seat comfort, which received the most negative reviews.

- Enhance service quality on low-rated aircraft: Aircraft models with
  consistently lower scores should be prioritized for upgrades.

For Business Analysts:

- Use the dynamic metric selection to track improvements or declines in
  customer satisfaction.

- Perform seasonal trend analysis to identify fluctuations in customer
  sentiment.

For Travelers:

- Use the dashboard to choose flights based on aircraft type and service
  ratings for a better travel experience.

# Conclusion

The **British Airways Customer Reviews Dashboard** offers a clear and
interactive way to analyze customer sentiment, highlighting service
strengths and areas for improvement. It enables business analysts and
airline executives to explore trends dynamically, helping track customer
satisfaction across different regions, aircraft models, and traveler
types.

Future enhancements like **real-time data integration, sentiment
analysis, and predictive analytics** could further refine insights,
allowing British Airways to proactively address customer concerns. With
these upgrades, the dashboard would become an even more valuable tool
for improving service quality and enhancing customer experience.

# References & Resources

- Data Sources: British Airways Review Dataset, Country Mapping Data.

- Tools Used: Tableau for visualization, Excel for data preprocessing.

- [Tableau Public Dashboard Link](https://public.tableau.com/shared/Z2GX48ND5?:display_count=n&:origin=viz_share_link)
