# CAR VEHICLE THEFT IN NEW ZEALAND 2021-2022

# 1.	Executive Summary
This report presents an analysis of vehicle theft incidents recorded by the New Zealand Police between 2021 and 2022. Using Power BI, the study explores patterns across vehicle types, brands, regions, and time. The analysis reveals significant variation in theft activity by location, vehicle characteristics, and time period. These insights can support law enforcement operations, insurance risk assessment, and policy formulation aimed at reducing vehicle-related crime.

# 2.	Introduction
Vehicle theft remains a significant public safety and economic concern in New Zealand. Beyond financial losses to individuals and insurers, vehicle theft places additional strain on law enforcement resources. This study aims to analyze vehicle theft data from 2021 to 2022 to identify key trends, high-risk regions, and commonly targeted vehicle types. The analysis is designed to support evidence-based decision-making using interactive Power BI dashboards.

# 3.	Data Description 
The dataset used in this study was obtained from Maven Analytics; a free dataset download platform where you can sample unique, real-word datasets designed to test data visualization and analytical thinking skills. and this data set covers reported vehicle theft incidents between January 2021 and December 2022. Key variables include vehicle type, make, model year, color, date of theft, and region. Population data was incorporated to calculate theft rates per region. The analysis assumes all reported incidents are accurately recorded; unreported thefts are not captured.

# 4.	Methodology
Data preparation involved cleaning blank values and rows, renamed columns, changed specific data types and creating calculated measures such as total vehicle stolen, total population, most stolen vehicle make, theft rates per population among others. Microsoft Power BI was used to build interactive dashboards, allowing for dynamic filtering by region, vehicle type, year, and other attributes. Visualizations include bar charts, table, line charts, card, donut chart, stacked bar chart etc.

# 5.	Data Analysis and Interpretation 
# 5.1.	Overview of Vehicle Theft 
The Executive Dashboard provides a high-level summary of vehicle theft activity across New Zealand during the study period. The analysis indicates that 4,553 vehicles were reported stolen across 16 regions. Certain regions consistently recorded significantly higher theft volumes, suggesting the presence of localized hotspots of vehicle-related crime.
At the vehicle level, station wagons emerged as the most frequently stolen vehicle type, indicating a disproportionate targeting compared to other categories. This pattern suggests that the practicality, accessibility, and functional design of station wagons; such as cargo capacity and widespread availability may increase their attractiveness to offenders. These characteristics may facilitate ease of use, resale, or parts recovery, making this vehicle type a preferred target for theft.

<img width="730" height="404" alt="image" src="https://github.com/user-attachments/assets/ab04b92d-fee2-4997-9bcd-a294505a0eac" />


# 5.2.	Time Based Trends
Analysis of vehicle theft incidents over time indicates a substantial increase in theft activity in 2022 compared to 2021. A total of 2,885 vehicles were reported stolen in 2022, up from 1,668 thefts in 2021, representing a 53.46% year-on-year increase. This sharp rise suggests a notable escalation in vehicle-related crime within the observed period. The monthly trend analysis reveals that March 2022 recorded the highest number of theft incidents, with 1,053 reported cases, making it the peak month across both years. This pronounced spike is a key contributor to the overall increase observed in 2022 and indicates a period of heightened theft activity.
It is important to note that the dataset covers incidents recorded between January to April and October to December, and therefore does not represent a full calendar year. Despite this limitation, the temporal distribution of thefts shows that the first quarter of 2022 accounted for 56.14% of all recorded thefts, highlighting a strong concentration of incidents early in the year. Further analysis of theft rates reinforces this trend. The theft rate increased from 0.03% in 2021 to 0.06% in 2022, effectively representing a doubling of the vehicle theft rate within the study period. This increase underscores the growing severity of vehicle theft and raises concerns regarding the effectiveness of existing prevention and enforcement measures during this time.

<img width="716" height="409" alt="image" src="https://github.com/user-attachments/assets/6e10ad01-09c8-4d45-ab05-cd7a81b539b8" />


# 5.3.	Geographic and Location Risk Analysis
Auckland (Location ID 102) recorded the highest number of vehicle thefts, with 1,638 reported incidents, making it the most affected region during the study period. In contrast, Southland recorded the lowest number of thefts, indicating comparatively lower vehicle theft activity. Additionally, the West Coast (Location ID 113), Tasman (Location ID 110), and Marlborough (Location ID 112) reported zero vehicle thefts, suggesting minimal or no recorded theft incidents in these regions. The gap between Auckland and Canterbury, the second-highest theft region, is substantial. Auckland’s theft count exceeds Canterbury’s by approximately 70%, highlighting a disproportionately high concentration of vehicle theft incidents in the Auckland region.
However, when theft is assessed relative to population size, a different risk pattern emerges. Gisborne recorded the highest theft rate (0.34) despite having a low population density of 6.21, indicating a higher per-capita risk of vehicle theft. In contrast, Auckland, while having the highest absolute number of thefts, recorded a lower theft rate of 0.10, despite its very high population density of 343.09.
This contrast is reflected in the theft rate ranking, where Auckland ranked sixth, following Canterbury, Northland, Bay of Plenty, Nelson, and Gisborne. These findings demonstrate that regions with lower population density may face higher relative theft risk, even if their total theft counts are comparatively low. This underscores the importance of considering population-adjusted theft rates, rather than absolute counts alone, when assessing regional vehicle theft risk and allocating resources.

<img width="705" height="406" alt="image" src="https://github.com/user-attachments/assets/89efff2f-c3e5-4494-92f8-d8c854851773" />


# 5.4.	Make and Model Performance Insights
Analysis of vehicle makes indicates that Toyota was the most frequently stolen manufacturer, with a total of 716 vehicles reported stolen between 2021 and 2022. When examined by vehicle category, standard vehicle types overwhelmingly dominated theft incidents, accounting for 95.81% of all vehicles stolen, while luxury vehicles represented only 4.19%. This distribution suggests that vehicle theft in New Zealand is largely concentrated among commonly owned, mass-market vehicles rather than high-end models.
Color-based analysis further reveals that silver vehicles were the most commonly stolen, indicating a potential preference linked to availability, resale demand, or reduced visibility. Interestingly, the make category with the highest number of thefts was trailers, highlighting that theft activity extends beyond traditional passenger vehicles and includes utility and transport-related assets.
An examination of model years shows that the 2006 saloon model was the single most stolen model, with 101 reported thefts, despite station wagons being the most frequently stolen vehicle type overall. This suggests that while station wagons dominate at the category level, specific models within other vehicle types may present heightened vulnerability, possibly due to older security features or higher circulation volumes.

<img width="715" height="410" alt="image" src="https://github.com/user-attachments/assets/d12c2907-9c0e-4444-9ca9-3987b1c1be65" />


# 6.	Interactive Dashboard Features
The Power BI report includes interactive slicers for vehicle type, make, model year, region, color, and date. These features enable users to perform self-service analysis, explore specific scenarios, and tailor insights to their operational or strategic needs.

# 7.	Key Findings 
•	Vehicle theft increased by 53.46% from 2021 (1,668) to 2022 (2,885).
•	March 2022 recorded the highest monthly thefts (1,053).
•	First quarter of 2022 accounted for 56.14% of all recorded thefts.
•	Theft rate doubled from 0.03% in 2021 to 0.06% in 2022.
•	Auckland had the highest theft volume (1,638 cases), 70% higher than Canterbury.
•	West Coast, Tasman, and Marlborough recorded zero thefts.
•	Gisborne had the highest per-capita theft rate (0.34) despite low population density.
•	Auckland ranked sixth in theft rate when adjusted for population.
•	Station wagons were the most stolen vehicle type.
•	Standard vehicles accounted for 95.81% of all thefts; luxury vehicles 4.19%.
•	Toyota was the most stolen make (716 vehicles).
•	Silver vehicles were the most commonly stolen color.
•	Trailers were the most stolen make category.
•	2006 saloon model had the highest theft count (101 vehicles) despite station wagons being the dominant type.
•	Older vehicle models are more vulnerable due to weaker security and higher circulation.

# 8.	Conclusion
The study demonstrates that vehicle theft in New Zealand between 2021 and 2022 is a growing and concentrated crime issue, particularly in urban centers such as Auckland. Time-based trends show seasonal spikes and a doubling of theft rates, while geographic and per-capita analysis reveals both high-volume and high-risk regions. Vehicle characteristics, including type, make, model year, and color, strongly influence theft patterns, with standard vehicles, station wagons, and older models being the most vulnerable.
These insights underscore the importance of data-driven strategies in addressing vehicle theft. Law enforcement can prioritize high-risk regions and periods, insurers can adjust premiums based on risk profiles, policymakers can develop targeted prevention programs, and manufacturers can enhance vehicle security for susceptible models. Continued monitoring and analysis will be critical to reducing vehicle theft and improving safety across New Zealand.

