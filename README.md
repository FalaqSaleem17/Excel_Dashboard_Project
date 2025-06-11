# **Road Accident Analytics Dashboard** 

## Description
I've developed a Road Accident Analytics Dashboard in Excel, visualizing 2021 and 2022 accident data. This dashboard provides valuable insights through visualizations, empowering stakeholders to make data-driven decisions for safer roads.

## Data Source
Data Download - https://docs.google.com/spreadsheets/d/1R_uaoZL18nRbqC_MULVne90h3SdRbAyn/edit?gid=1319047066#gid=1319047066

## Skills showcased in this Dashboard
📊 Data Analysis & Visualization
- Data cleaning and preparation using Excel tools (e.g., filters, sorting, text functions)
- Creation of dynamic pivot tables to summarize accident data by location, time, cause, severity, etc.
- Use of pivot charts for visual insights (bar, column, pie, Doughnut Charts, line charts)

📈 Dashboard Design
- Designed interactive dashboard layout using Excel features (slicers, charts, Text Box)
- Applied design principles to ensure readability, clarity, and usability
- Used named ranges and form controls to enhance interactivity

📂 Data Management
- Imported and structured data from external sources (CSV, Excel, etc.)
- Normalized data for analysis by removing duplicates and correcting inconsistencies
- Used data validation to prevent input errors

## Objective and KPIs
Objective:
- To develop a comprehensive dashboard that provides insights into road accident data for the years 2021 and 2022, enabling     year-over-year comparisons and detailed analysis across multiple dimensions.

Primary KPIs:
- Total Casualties for the Current Year (2022) and Year-over-Year (YoY) Growth
- Total Accidents for the Current Year and YoY Growth
- Total Casualties by Accident Severity (e.g., Fatal, Serious, Slight) for the Current Year and YoY Growth

Secondary KPIs:
- Total Casualties by Vehicle Type for the Current Year
- Monthly Casualty Trends:
   + Comparative line/bar chart showing monthly casualties for both the Current Year and the Previous Year
- Casualties by Road Type (e.g., Motorway, A Road, B Road) for the Current Year
- Casualties by Area Type and Time of Day for the Current Year:
   + Breakdown by Urban/Rural and Day/Night
- Total Casualties and Total Accidents by Location
   + Geographical breakdown (e.g., city, region, or postal area)

## Data Cleaning and Transformation
The data preparation phase began with a thorough exploration of the dataset to identify and resolve quality issues. Key steps included:
- Identifying and Handling Data Quality Issues:
   + Checked for null values, blank fields, and potential data entry errors.
- Removing Redundancies:
   + Eliminated duplicate records and dropped irrelevant or unnecessary columns.
- Ensuring Data Consistency:
   + Standardized data types, formats, and value conventions across all fields to ensure uniformity and accuracy.
- Feature Engineering:
   + Created two new attributes—'Year' and 'Month'—to support logical grouping, filtering, and time-based analysis.

## Data Analysis
A dedicated "Data Analysis" sheet was created to consolidate key insights using pivot tables, making it easier for new users, developers, or clients to navigate and interpret the data efficiently.
- A total of nine pivot tables were developed on this sheet to summarize and explore critical patterns and trends within the dataset.
- These pivot tables focus on examining the relationship between the number of casualties and various factors such as:
    + Casualty Type
    + Vehicle Type
    + Road Type
    + Location
- In addition, monthly trends were analyzed for both 2021 and 2022, allowing for effective comparison and time-based insights.

This structured summary provides a clear, accessible foundation for deeper analysis and informed decision-making.

<img width="960" alt="Data Analysis" src="https://github.com/user-attachments/assets/77329550-44f7-4694-be07-08a7271dffbd" />


## Data Visualization
**Dashboard Development**
The final dashboard was built by inserting and customizing pivot charts derived from the corresponding pivot tables, ensuring a clear and visually engaging presentation of insights.

To enhance user experience and interactivity, the following features were integrated:
- Slicers and Timelines for dynamic filtering and easy exploration of the data across different dimensions (e.g., year, month, location).
- Hyperlinks and Navigation Controls were added to key icons and sections, enabling seamless movement between different parts of the dashboard.

The result is a user-friendly, interactive dashboard designed to support quick insights and efficient decision-making.

<img width="960" alt="Road Accident Analytics Dashboard 1" src="https://github.com/user-attachments/assets/3f3559bf-8703-4944-bd66-5e9950e9cb2d" />

<img width="959" alt="Road Accident Analytics Dashboard 2" src="https://github.com/user-attachments/assets/e2c25d99-cc4c-4062-88d4-969304724a8f" />

## Key Insights
📈 Scale of the Issue: 417,883 casualties occurred over the two years, highlighting the urgent need for road safety improvements. 

📅 Seasonal Trends: While casualties were slightly higher in 2021, both years saw peaks in October and November, with lows in January and February. This suggests a potential correlation with seasonal factors. 

🚗 Vehicle Type Impact: Car accidents accounted for a significant 79.8% of total casualties, emphasizing the importance of car safety measures. 

🩸 Severity Distribution: Thankfully, most casualties (84.1%) were of slight severity, with fatal casualties representing only 1.7%. 

🛣️ Road Type & Surface: Single-carriageway roads saw the highest number of casualties (310.1K), while slip roads had the lowest (5.1K). Dry road surfaces accounted for 67% of casualties, likely due to higher traffic volume during good weather. 

🌧️ Location & Light Conditions: Urban areas contributed to the majority of casualties (61%), and daylight conditions were associated with 73% of incidents.
These insights provide a valuable foundation for targeted interventions and data-driven decision-making to improve road safety.

## Strategic Recommendations
Based on the monthly and categorical analysis of road accident casualties, the following targeted actions are recommended to enhance road safety and reduce casualties:

📅 Target High-Risk Months (October & November)
- The dashboard highlights October and November as peak months for casualties in both years.
- Traffic authorities and stakeholders should intensify road safety campaigns, enforcement, and monitoring during these periods to mitigate risks.

🚗 Focus on Car Drivers
-As car drivers account for the majority of casualties, they should be the primary focus for awareness initiatives, including:
  - Road safety workshops and campaigns
  - Strict traffic law enforcement
  - Routine safety checks and driving behavior assessments

🛣️ Enhance Safety on Single Carriageway Roads
- With the highest number of casualties reported on single carriageway roads, there is a pressing need to:
  - Implement additional safety measures (e.g., signage, speed regulation)
  - Upgrade to dual carriageways where feasible to reduce head-on collisions and improve traffic flow

🌧️ Improve Road Surface Conditions
- Analyzing casualty patterns across road surfaces reveals the importance of:
  - Regular road maintenance
  - Surface enhancements, especially in high-traffic or accident-prone areas

🏙️ Target Urban Areas for Safety Improvements
- Since urban areas contribute to 61% of casualties, focused interventions such as:
  - Improved pedestrian infrastructure
  - Smart traffic signals and signage
  - Public awareness programs should be prioritized, especially during daytime, when 73% of accidents occur.
 
## Conclusion
- The analysis of road accident data from 2021 and 2022 provides valuable insights into patterns of casualties and highlights critical areas for intervention. Key findings indicate that car drivers, urban areas, and single carriageway roads are major contributors to overall casualty figures. Furthermore, the months of October and November emerge as high-risk periods, demanding increased vigilance and targeted safety efforts.
- By leveraging these insights, stakeholders—including traffic authorities, urban planners, and policymakers—can implement strategic measures to improve road safety. Focused awareness campaigns, infrastructure upgrades, and stricter monitoring during high-risk periods can play a vital role in reducing casualties and enhancing public safety.
- This data-driven approach ensures that resources are directed where they are most needed, paving the way for smarter, safer, and more responsive road safety initiatives.
