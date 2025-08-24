# London UK Real Estate Dashboard (2022)

## Project Objective
The objective of this project is to provide an interactive dashboard for London UK real estate in 2022. It is designed for prospective buyers, real estate agents, and companies to quickly gain insights into property prices, sales trends, and popular districts in London. The dashboard allows users to identify hot areas, property types, and seasonal trends to make informed decisions.

## Dataset Used
[Dataset](https://www.kaggle.com/datasets/hm-land-registry/uk-housing-prices-paid) from Kaggle 

## Questions / KPIs
- Which districts in London had the highest median property prices in 2022?  
- What are the most common types of properties sold (Detached, Semi-Detached, Flats, Terraced)?  
- How many properties were sold each month, and what was the median price trend?  
- What was the largest month-over-month change in sales volume?  
- How does distance from the city center affect price and sales volume?  

## Process
- Extracted raw data from Kaggle.  
- Performed preliminary cleaning in Excel: examined data for missing values, outliers, and inconsistencies.  
- Filtered data specifically for the latest year, 2022, and for London, UK.  
- Imported filtered data into Power BI.  
- Cleaned further using Power Query:  
  - Standardized property type letters to full text (e.g., `D = Detached`).  
  - Removed blanks and redundant/unused columns.  
- Created pivot tables and visualizations in Power BI to answer the KPIs.  
- Combined visuals into a single interactive dashboard with slicers for dynamic filtering.  

## Dashboard
![London Housing Dashboard](https://github.com/youneselkaisi/London-Real-Estate-Dashboard/blob/main/London%20Housing%20Dashboard%20Image.png)

## Project Insights
- Median home price in London for 2022 was £578,000.  
- Total properties sold in 2022: 59,100.  
- Flats were the most commonly purchased property type, followed by terraced and semi-detached homes.  
- Flats are especially popular closer to the city center and are generally the cheapest, while detached homes are the most expensive.  
- Property price and sales volume gradually increased in spring, peaked in summer, and declined in fall and winter.  
- Largest month-over-month increase in sales: February → March (+17.2%).  
- Largest month-over-month decreases: March → April (-11.9%) and September → October (-8.9%).  
- Districts closer to the city are more expensive, while those further away are much cheaper.  

## Conclusion
The London Real Estate Dashboard provides valuable insights into the property market for 2022. It highlights trends in property types, seasonal sales patterns, and district-level pricing, helping buyers and real estate professionals make informed decisions. Understanding that flats dominate city-center sales and detached homes remain the premium option allows for strategic planning in both investment and purchasing decisions.
