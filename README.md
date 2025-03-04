# Resturant_Ratings


## Table of Contents 

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Summary](#summary)
- [Recommendation](#recommendation)
- [Limitations](#limitations)


## Project Overview
---
The project aims to analyze consumer preferences, restaurant ratings, and market demand-supply gaps to identify the best restaurant investment opportunities based on data-driven insights.

`Consumer Preferences (consumer_preferences.csv)`
`💡 Purpose: Identifies the preferred cuisine type for each consumer`

`Consumer_ID:- Unique identifier for each consumer`
`Preferred_Cuisine:- The cuisine type preferred by the consumer (e.g., Mexican, Italian, Chinese)`

`Consumers (consumers.csv)`
`💡 Purpose: Provides demographic details about consumers to analyze market trends & biases`

`Consumer_ID:-	Unique consumer identifier`
`City:-	City where the consumer lives`
`State:-	State where the consumer lives`
`Country:-	Country of residence`
`Latitude & Longitude	Geolocation coordinates`
`Smoker:-	Whether the consumer smokes (Yes/No)`
`Drink_Level:- Frequency of alcohol consumption`
`Transportation_Method:-	How they commute (Public/Private/Walk)`
`Marital_Status:-	Single/Married`
`Children:-	Whether they have children (Yes/No)`
`Age:-	Age of the consumer`
`Occupation	Job category (Student, Employee, etc.)`
`Budget	Spending category (Low, Medium, High)`

`Ratings (ratings.csv)`
`💡 Purpose: Stores customer ratings for different restaurants`

`Consumer_ID:- ID of the customer who gave the rating`
`Restaurant_ID:- ID of the restaurant being rated`
`Overall_Rating:- Overall rating given by the consumer (scale unknown, but likely 1-5)`
`Food_Rating:- Rating given for food quality`
`Service_Rating:- Rating given for service quality`

`Restaurant Cuisines (restaurant_cuisines.csv)`
`💡 Purpose: Contains restaurant details like location, pricing, and policies`

`Restaurant_ID:- Unique restaurant identifier`
`Name:- Restaurant name`
`City:-	City where the restaurant is located`
`State:-	State where the restaurant is located`
`Country:- Country where the restaurant operates`
`Latitude & Longitude	Geolocation coordinates`
`Alcohol_Service:- Whether alcohol is served (Full Bar/None/etc.)`
`Smoking_Allowed:-	Whether smoking is allowed (Yes/No)`
`Price:- Pricing category (Low/Medium/High)`
`Franchise	Whether it's a franchise (Yes/No)`
`Area:-	Type of area:- (Urban, Suburban, etc.)`
`Parking:-	Type of parking available`


## RESTAURANT_RATING_DASHBOARD 
![Restaurant Dashboard](https://github.com/user-attachments/assets/59e6cd2a-ebf1-4388-983c-d9e97110ec98)

![Customers demographics](https://github.com/user-attachments/assets/c5d864c6-0029-4cfc-b514-4a5011f3e295)


### Data Sources 

the primary dataset used for this analysis is the "Restaurant_Ratings CSV" file, containing detailed information about sales made throughout the years.


#### Tools

- Microsoft Excel - Structured data organization, summary tables, and report generation.
   - [Download here](https://mavenanalytics.io/data-playground?order=date_added%2Cdesc&search=Restaurant)
- PowerBI - Interactive dashboards for tracking restaurant trends, demand-supply gaps, and location analysis.

 ### Data Cleaning

 in the initial data preparation phase, I performed the following tasks:
 1. data loading and inseption
 2. handling missing value
 3. data cleaning and formatting 

### Exploratory Data Analysis 

EDA helps uncover patterns, trends, and relationships in the data before making business decisions. Below is a breakdown of key insights from the datasets.

1.	Understanding Consumer Preferences 

2.	Analyzing Restaurant Ratings

3.	Consumer Demographics & Behavior

4.	Location-Based Analysis

   
### Data Analysis

The data analysis focused on consumer preferences, restaurant ratings, and market demand-supply gaps to identify business opportunities in the restaurant industry.


### Results

- Mexican cuisine is the most preferred, but Coffee Shops, Latin American, and Hot Dogs have high demand with very few restaurants—a major market gap.

- High-rated restaurants don’t always match demand—good service and food quality are key factors for success.

- Young consumers (21-25, students, medium budget) dominate the market, preferring affordable, fast-casual dining.

- Best locations for investment: University areas, business districts, and high-foot-traffic zones with low competition.

  
### Summary

This analysis identifies profitable restaurant investment opportunities by studying consumer preferences, restaurant ratings, and market demand-supply gaps.

## Recommendation 
Based on the analysis We recommend the following actions:
- Invest in High-Demand, Low-Supply Cuisines – Coffee Shops, Latin American, and Hot Dogs have high demand but few restaurants, making them great opportunities.
- Target Young, Budget-Conscious Consumers – Most customers are 21-25 years old, students, and prefer affordable, fast-casual dining.
- Improve Service & Food Quality – High ratings come from consistent food and good service, not just popular cuisine.
- Expand to Underserved Locations – Focus on university areas, business districts, and high-foot-traffic zones with low competition.

### Limitations
- Geographic Restriction – The data is limited to Mexico, so insights may not apply globally.
- Demographic Bias – Most consumers are young (21-25), students, and single, which may not represent all dining habits.
- Missing & Incomplete Data – Some restaurant details, customer demographics, and ratings were incomplete or inconsistent, affecting accuracy.
- Lack of Financial Data – No information on restaurant revenue, costs, or profitability, limiting financial projections.



😃

💻

🍴 
|Heading1|Heading2|
|--------|--------|
|Microsoft Excel|PowerBI| 






