# Optimizing Real Estate Pricing Strategy for Maximized Profits.

![image](https://github.com/stephaniemwai/dsc-phase-2-project-v2-3/assets/143871178/ec0c4528-2217-4644-b7ca-78981466aa09)


## Project Overview:

Premiere Property Group, a prominent real estate agency in King County, has experienced a decline in profits over the past three years. To address this challenge, the agency has sought analytical expertise to devise a strategic pricing approach aimed at optimizing profits.

This initiative involves a deep dive into the vast array of housing data from King County, focusing on pivotal factors that influence house prices. Central to this analysis are variables such as the age of properties, their condition and ratings within different locations, the presence of views and waterfronts, and the impact of seasonal trends on sales.

The ultimate goal is to establish a comprehensive pricing strategy that not only maximizes profits for Premiere Property Group but also adapts to the fluctuating dynamics of the King County real estate market.
![download](https://github.com/LCR2022/dsc-phase-2-project-v2-3/assets/99391873/300df1d0-d736-46ea-9e89-17089aa5fcfe)

### General Objective:

To develop a comprehensive and data-driven pricing strategy that maximizes profitability for Premiere Property Group by thoroughly analyzing various factors influencing house prices in King County.

This general objective encompasses the overarching aim of the project, focusing on leveraging data analysis to enhance the agency's pricing approach in response to the recent decline in profits.

### Business Problem
In this project our main focus is the need to provide advice to homeowners about how home renovations might increase the estimated value of their homes, and by what amount. The following questions helped us in using exploratory analysis to analyse the data and give conclusive recommmendations for the homeowners. These include the following:
i) Does the age of the house(year built) have an impact on its selling price? Are there any patterns or trends that can guide pricing decisions?
ii) Is there a corelation between the condition/rating of a house, especially location and the resulting sales price?
iii) Is there a seasonal effect on the sales price of homes? For example, do homes sold during the winter season command higher prices compared to other months and how can this knowledge be leveraged for strategic pricing?
iv) What extent do the views and waterfront accessibility influence the property pricing? Does this feature impact overall value of the property.

Specific Objectives
![Uploading image.png…]()

**Age and Price Analysis:** Determine the impact of a house's age (year built) on its selling price and identify any significant patterns or trends that can be utilized in pricing strategies.

**Condition/Grade and Location Impact:** Assess the correlation between the condition or rating of a house and its sales price, especially considering the property's location, to understand how these factors influence valuation.

**Seasonal Pricing Trends:** Investigate if there are seasonal variations in house prices, particularly examining if houses sold in winter have different pricing dynamics compared to other seasons, and how this knowledge can be applied strategically.

**Effect of Views and Waterfront Accessibility:** Quantify the extent to which views and waterfront accessibility influence property pricing, and determine the value addition of these features to the overall property valuation.

**Waterfront Price Correlation Analysis:** Specifically analyze how the presence of a waterfront correlates with house prices and the premium it adds to property values.

**Grade Score Correlation Study:** Examine the relationship between the newly engineered grade score and selling prices, to understand how this metric reflects on property valuation.

These specific objectives are designed to address each of the research questions in detail, providing a structured approach to understanding the key drivers of house prices in King County. This approach will enable Premiere Property Group to make informed, data-backed decisions in their pricing strategies.

### The Data

Data

Utilizing the King County Housing Data Set, which encompasses details such as house size, location, condition, and various features, this project endeavors to construct an advanced multiple regression model. The primary objective is to develop a predictive model that can accurately estimate a house's price by incorporating the key factors. The emphasis is on optimizing the model's precision to enable effective predictions in the dynamic real estate landscape of King County.

### Column Names and descriptions for King County Data Set
* **id** - unique identified for a house
* **date** - Date house was sold
* **price** - Price is prediction target
* **bedrooms** - Number of Bedrooms/House
* **bathrooms** - Number of bathrooms/bedrooms
* **sqft_living** - square footage of the home
* **sqft_lot** - square footage of the lot
* **floors** - Total floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
  
### Findings, Conclusion & Recommendations:

![png](Phase2_Project_files/Phase2_Project_76_0.png)

Age of the house vs Price

![png](Phase2_Project_files/Phase2_Project_84_0.png)

Grade vs Price

![png](Phase2_Project_files/Phase2_Project_86_0.png)


![png](Phase2_Project_files/Phase2_Project_86_1.png)

Seasonal Pricing

![png](Phase2_Project_files/Phase2_Project_88_0.png)

Location vs Price

![png](Phase2_Project_files/Phase2_Project_90_1.png)

## __Final Recommendations:__

Dynamic Pricing Strategy:
Implement a pricing strategy that accounts for property size (especially living area square footage), location (specific zipcodes and cities), and property features (like condition and grade).
Emphasize premium features like large living spaces, desirable locations, views, and waterfront access in pricing and marketing efforts.

Seasonal Marketing and Sales Tactics:
Capitalize on the higher market activity and prices in Spring and Summer for listing and selling properties.
Consider more competitive pricing and marketing strategies in Fall and Winter to attract buyers during slower market periods.

Location-Focused Investment:
Identify and invest in areas with high-demand zipcodes and emerging markets.
Leverage insights from location-based analysis to make informed decisions about property acquisitions, developments, or renovations.

Data-Driven Decision Making:
Continue to use data analytics for informed decision-making in all aspects of real estate transactions, from pricing to marketing to investment strategies.




Based on the findings, the following was concluded:
