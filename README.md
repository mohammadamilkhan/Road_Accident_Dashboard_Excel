# Road Accident Dashboard

## Project Overview
This project aims to develop a Road Accident Dashboard for the years 2011 and 2022 to provide key insights into accident trends and patterns.

## Objectives

### Primary KPIs
- Determine the total number of casualties resulting from road accidents.
- Analyze casualty distribution by accident severity and calculate the percentage of casualties within each severity category.
- Identify the vehicle type with the highest number of casualties and its overall contribution to the total.

### Secondary KPIs
- Evaluate the total casualties for each vehicle type to understand risk distribution.
- Analyze the monthly trend of casualties, comparing data from 2021 and 2022 to identify patterns or anomalies.
- Identify the road type with the highest number of casualties to assess infrastructure-related risks.
- Examine the distribution of casualties based on road surface conditions to understand environmental factors affecting accidents.
- Assess the relationship between accident locations (urban/rural) and time of occurrence (day/night) to determine high-risk areas and periods.

## Data Cleaning & Preprocessing
- Created "Month" and "Year" columns from the Accident_Date field using the TEXT function to enable time-based analysis.
- Corrected a typographical error in the Accident_Severity column, where "Fetal" was mistakenly written instead of "Fatal," using the Find and Replace function.
- Performed a null or blank value check across the dataset to ensure data integrity and consistency.

## Key Findings & Conclusions

### 1. Casualty Reduction Trend (2021 vs. 2022)
- Overall, casualties declined in 2022, indicating potential improvements in road safety measures.

### 2. Casualties by Severity
- 84% of casualties involved slight injuries, while only 1.71% were fatal.
- Although the fatality rate is low, it still accounts for over 7,000 deaths, highlighting the need for continued safety efforts.
- Serious injuries (14.19%) remain a concern, necessitating targeted interventions.

### 3. Impact of Vehicle Type on Casualties
- Cars contribute to nearly 80% of casualties, making them the primary focus for safety measures.
- Agricultural vehicles and other types account for a minimal percentage, indicating the need for interventions to focus on passenger and commercial vehicles.

### 4. Factors Contributing to the Decline in Casualties (2022)
- Improved road safety policies and enforcement.
- Reduced traffic in certain months due to external factors such as lockdowns and weather conditions.
- Increased public awareness and advancements in vehicle safety technology.

## Recommendations & Next Steps

### 1. Enhancing Road Safety for High-Casualty Vehicle Types
- Introduce stricter speed regulations, lane discipline enforcement, and driver education programs.
- Invest in automated traffic enforcement (speed cameras, red-light cameras) to curb reckless driving.

### 2. Addressing High-Risk Time Periods
- Focus on months with increased casualties (e.g., February) and analyze contributing factors (weather, traffic flow, events, etc.).
- Implement seasonal road safety campaigns and targeted traffic law enforcement during high-risk periods.

### 3. Improving Road & Surface Conditions
- Identify and improve high-risk road types by enhancing lighting, signage, and maintenance.
- Use anti-skid road materials and better drainage systems to reduce weather-related accidents.

### 4. Day vs. Night Accidents
- While nighttime casualties are lower, enhancing street lighting, reflective road signs, and vehicle visibility remains essential.
- Conduct stricter night-time DUI (driving under influence) and speeding checks to further minimize risks.

### 5. Data-Driven Policy Making
- Implement real-time accident monitoring systems using IoT and sensor data.
- Utilize AI-driven predictive models to identify high-risk zones and proactively prevent accidents.

### 6. Community Awareness & Training
- Conduct driver training programs on defensive driving techniques.
- Launch public awareness campaigns about accident-prone areas and road safety best practices.

## Final Conclusion
The data suggests a positive trend in casualty reduction in 2022, but inconsistencies in some months and high-risk vehicle types require targeted interventions. By focusing on enforcement, infrastructure improvements, and public awareness, further reductions in casualties can be achieved. A data-driven approach will ensure continuous improvements in road safety policies, making roads safer for all users.
