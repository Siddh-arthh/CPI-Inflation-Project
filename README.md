# CPI-Inflation-Project
Analyzed India’s CPI data using Excel to track inflation trends across Food, Fuel, Housing &amp; more. Cleaned, visualized, and extracted insights to understand price movement across sectors—helping businesses and policymakers make informed decisions.

Problem Statement:
You are working with the National Statistical Office, which is equipped to release inflation numbers in India. As an analyst, you are provided with CPI data and are expected to find out insights from the data. Your senior wants you to find key trends and deep dive into the data to answer the following questions:

# DATA CLEANING
## Steps taken to clean the data
1) to fill the missing rows in aprial amd may 2020 I have used backward filling by making use of filter in Urban,rural,urban and rural
2) there are missing values in Housing(NA and -) those I have replaced with 0 as any other values will definitely effect the data as it is empty for Rural areas mostly
3) the Given Border categories like (food and bevarages) and (clothing and foot ware) are not considerable as they are not having the averages or any other relation to there individual columns
4)there was a spelling mistake in the month of march and it was corrected 
5)as pivot table was not giving me the sum values for housing data I did it seperately and added it to the above mentioned table 

<img width="1860" height="435" alt="categorizatiopn" src="https://github.com/user-attachments/assets/ad75d20c-10a3-4ae3-9150-9de3436d7531" />

## 1.	Based on the latest month's data, identify the contribution of different broader categories (food, energy, transportation, education, etc.) towards the CPI basket. Broader categories (buckets) can be created by combining similar categories can be grouped into one bucket; Example: Meals, Beverages, and Cereals can be clubbed to create the "Food" category, etc.

# •	Which broader category has the highest contribution towards CPI calculation?

## Observations:
Inflation is heavily food-driven: Half of the total inflation weight comes from food-related categories.  
Essential categories like Housing, Health, and Education maintain a consistent contribution (~3.8–3.9%).  
Discretionary categories like Luxury and Tobacco have a notable share, suggesting lifestyle inflation is not negligible.  
Transport and Communication have a relatively lower impact at 3.51%, which is surprisingly modest compared to its typical volatility.  

 ##  2.	A trend of Year-on-Year (Y-o-Y) increase in CPI (rural + urban) inflation starting from 2017 for the entire basket of products combined.
### •	Create a graph depicting the growth rate Y-o-Y and identify the year with the highest inflation rate.
<img width="913" height="320" alt="image" src="https://github.com/user-attachments/assets/14d4b833-b0a7-4809-b91f-c269ab85a86b" />

India experienced high inflation in 2022 primarily due to a combination of global and domestic factors, many of which were interconnected.  
Following are some of the reasons:  

1) Oil price surge due to Russia-Ukraine war  
2) Supply chain issues post-COVID and China lockdowns  
3) Rising food prices from poor weather and global shortages.  
4) Weak rupee increased import costs.  
5) Global commodity price spike.  
6) High core inflation in services and housing.

### •	Highlight the reason why the year has the highest inflation (based on research).  
• Urban areas experienced a sharper and more sustained inflation rise post-2019, likely due to higher exposure to service disruptions, supply chain issues, and fuel price hikes during and after the lockdown.  
• Rural inflation, although initially higher, became more volatile, reflecting varying impacts on agriculture, transport, and rural demand.  
• The data highlights how urban consumers bore a slightly greater inflationary burden during the pandemic years.  
  
<img width="782" height="382" alt="image" src="https://github.com/user-attachments/assets/0862636a-8d30-416c-83ef-a9d68b3c9fc2" />

## 3.	With India's retail inflation reaching a 3-month high of 5.55% in November 2023, largely due to a sharp rise in food prices, analyze the following for 12 months ending May 2023:
### •	Investigate trends in the prices of the broader food bucket category and evaluate month-on-month changes. Highlight the month with the highest and lowest food inflation.  
<img width="588" height="237" alt="image" src="https://github.com/user-attachments/assets/321fa2a1-e5c6-4401-a132-3ac38725baf2" />  

In 2022, spices in India experienced significant inflation due to a combination of factors:  

1) Adverse Weather Conditions: Heatwaves and erratic monsoon rains led to reduced crop yields for spices like cumin and coriander.  
2) Increased Export Demand: Global demand for Indian spices surged, leading to higher exports and reduced domestic availability.  
3) Supply Chain Disruptions: Events like Cyclone Biparjoy disrupted transportation, affecting the distribution of spices within the country.  
4) Persistent High Inflation Rates: The inflation rate for spices remained in double digits throughout the year, peaking at 21.09% in January 2023.   

These factors collectively contributed to the steep rise in spice prices in India during 2022.


### •	Identify the absolute changes in inflation over the same 12-month period and determine the biggest individual category contributor (only within the broader food category) towards inflation.  

<img width="1729" height="535" alt="image" src="https://github.com/user-attachments/assets/eb03e0b6-be7f-41e7-9e4c-9cd2aa8b3672" />

• The diagram visually tracks the Month-on-Month (M-o-M) inflation trend in percentage terms from June 2022 to May 2023.
• Blue bars represent increases, orange bars represent decreases, and gray indicates no change.

🔼 Months with Highest Increases (Inflation Peaks):
• October 2022: +0.8% (Highest spike in inflation)
• September 2022 and May 2023: +0.6% each
• April 2023 and January 2023: +0.5% each



🔽 Months with Decrease in Inflation:
• December 2022: -0.5% (Most significant drop)
• November 2022: -0.1%


#### Overall Trend Insight:
• The diagram shows a generally rising trend in inflation with brief dips in Nov and Dec 2022.
• After the dip in December, inflation steadily increased again toward May 2023, indicating a recovery or renewed price pressures.


## 4.	Investigate how the onset and progression of the COVID-19 pandemic affected inflation rates in India.
### •	Analyze the impact of key pandemic milestones (e.g., first lockdown) on the CPI inflation %, specifically focusing on categories like healthcare, food, and essential services.
<img width="2283" height="868" alt="image" src="https://github.com/user-attachments/assets/1afa8c93-596c-457a-b554-03a52c37fbcd" />
  
The data underscores the vulnerability of critical services to systemic shocks like pandemics.  

• Transport and Communication:Inflation jumped from 3.7% to 12.9% — highest increase among all categories.  
• Likely driven by fuel price hikes, supply chain disruptions, and logistics costs.  
• Miscellaneous: Rose from 3.2% to 7.4%, indicating a broad rise in prices of various non-essential goods and services.  
• Health: Increased from 1.6% to 6.6% — over 4x rise, possibly due to higher demand for medicines, healthcare services, and PPE.  
• Food: Slight rise from 8.8% to 8.9%, suggesting continued pressure but relatively stable food prices.  
• Education: Marginal increase from 2.2% to 2.7%, possibly due to digital learning infrastructure costs.  
####  Conclusion:  
• The pandemic disproportionately impacted sectors linked to mobility, healthcare, and essential services.  
• Transport and health sectors saw the most significant rise in inflation due to disrupted logistics, increased demand, and global supply chain shocks.

## 5.	Investigate how major global economic events (such as imported crude oil price fluctuations) have influenced India's inflation. This can include an analysis of crude oil prices and their trend.
### •	For the purpose of this analysis, focus only on the imported oil price fluctuations for years 2021 to 2023 (Month-on-month).  
### •	Identify trends in oil price change with change in inflation prices of all the categories and identify the category whose inflation prices strongly change with fluctuations in imported oil price.

  <img width="1343" height="516" alt="image" src="https://github.com/user-attachments/assets/b187cd51-02a9-4c0d-9fad-c76e34d93fee" />


#### Impact of Oil Price Fluctuations on Inflation in India (2021–2023)  
• Strongest Correlation:  
Transport and Communication (75.0%) showed the highest correlation with oil price changes, indicating that this sector is most sensitive to global oil price fluctuations due to direct dependency on fuel costs.  
• High Correlation:  
Fuel and Light (65.9%) and Food (65.9%) also showed a strong correlation, reflecting the cascading impact of oil prices on logistics, food distribution, and household energy consumption.  
Miscellaneous (63.7%) and Clothing & Footwear (63.7%) likely experienced inflation due to increased transportation and production costs linked to oil.  
• Moderate Correlation: 
Categories such as Luxury (61.6%), Household Goods & Services (60.5%), Health (56.0%), Education (55.2%), and Housing (55.3%) showed a moderate link, possibly due to indirect effects like increased operational and manufacturing expenses.  
• Lowest Correlation:  
Pan, Tobacco, and Intoxicants (45.2%) had the weakest correlation, suggesting this sector is less affected by oil price variations and more influenced by taxation and regulatory policies.

####  Conclusion  
    • Transport and fuel-related sectors are most vulnerable to global oil price changes.
    • Supply chain-driven categories, such as food and consumer goods, also experience a noticeable impact.
    • Non-essential or regulated sectors show relatively lower sensitivity.






