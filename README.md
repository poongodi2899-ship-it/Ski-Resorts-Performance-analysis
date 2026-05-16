  # Ski Resort Performance Analysis Dashboard – 2022
  ## PROJECT OVERVIEW:
           This project focuses on analysing data to uncover meaningful insights,
           trends, and patterns that support business decision-making.
         What is the project about?
                 This project analyzes ski resort data using Power BI to identify pricing,
                seasonal, and resort performance trends. Interactive dashboards and visualizations
                 were created for better analysis.
         What Problem are you solving?
                The analysis helps identify differences in resort distribution, pricing patterns,
               and operational performance across countries and continents. It simplifies complex
                data into meaningful insights.
         Why is the analysis important?
               This project supports data-driven decision-making using interactive charts,
               KPI cards, and slicers. It helps understand resort trends, seasonal demand, and
               business performance effectively.
               
    ## OBJECTIVES:
          The key objectives of this project are:
             To analyze the geographical distribution of ski resorts across different
             continents and countries using pie charts and clustered bar chart
             visualizations for better regional comparison and tourism analysis.
            To evaluate average resort pricing trends across countries and continents
             using clustered column charts and line charts in order to identify premium
              tourism regions and pricing variations.
              To compare beginner, intermediate, and difficult slope categories using
              stacked chart analysis to understand skiing difficulty distribution and customer
              accessibility across resorts.
            To examine the relationship between lift capacity and resort operational
             performance using scatter chart visualization for identifying infrastructure
              efficiency and visitor management capability.
            To develop an interactive Power BI dashboard using KPI cards, slicers, and
             multiple charts for dynamic filtering, real-time analysis, and effective business
             performance monitoring.
           To generate meaningful descriptive, diagnostic, predictive, and prescriptive
             analytics insights that support data-driven decision-making, tourism planning,
            and resort management strategies.
            
      ##  Data Sources:
               Dataset Source: https://mavenanalytics.io/data
               Timeline: 2022
               Data Size: 500+ rows and 25 columns

       ## Tools &Technologies:
Excel:
     Data Cleaning,
     Transformation
    Power BI
     Data Cleaning (Power Query)
     Data Modelling
     DAX Calculations
     Visualizations,
     Interactive dashboard creation.
## POWER BI:
     Data Cleaning and Transformation in Power BI
               The ski resort dataset was cleaned and transformed using Power Query
               Editor in Power BI to improve data quality, consistency, and analytical accuracy
               before creating the dashboard visualizations.

 Data Cleaning Steps Performed
            1. Removed Null and Blank Values
                 Blank and null records present in important columns such as Country,
                 Continent, Price, and Lift Capacity were identified and removed to avoid incorrect
                  analysis and visualization errors.
            2. Checked Duplicate Records
                 Duplicate ski resort entries were verified and removed to maintain accurate
                 resort counts and operational analysis.
            3. Changed Data Types
                Columns were converted into appropriate data types:
                Text format for Country, Resort, and Continent
                Decimal number format for Price and Lift Capacity
                Whole number format for Total Slopes and Highest Point
      This improved calculation accuracy and chart performance
            4. Renamed Column Headers
                 Column names were cleaned and standardized for better readability and easier
                dashboard development.
              Example:
                lift capacity → Lift Capacity
                longest run → Longest Run
           5. Created Price Category Column
                   A calculated column was created to categorize resorts into:
                    Low Price
                    Medium Price
                   High Price
        This helped perform pricing comparison analysis using charts and slicers.

           6. Filtered Unnecessary Data
             Irrelevant columns and unwanted records were removed to improve
             dashboard performance and reduce dataset complexity.
           7. Applied Sorting and Formatting
            Country names, continent values, and seasonal data were standardized to
           maintain consistent visualization results across charts and slicers.
           8. Created DAX Measures
       DAX measures were created for:
       Total Resorts
       Average Price
       Total Slopes
       Total Lift Capacity
       Maximum Highest Point
       Average Longest Run
These measures were used in KPI cards and interactive dashboard analysis.
           9. Improved Data Consistency
               Data validation and formatting ensured that all visualizations displayed
               accurate and meaningful insights without inconsistencies.
          10. Final Prepared Dataset
  After completing the cleaning and transformation process, the dataset
became ready for advanced analysis, dashboard creation, and interactive reporting
in Power BI.
## Data Modelling:
      Data modelling was performed to organize the dataset structure and ensure
      proper relationships and data consistency for reporting.
 Used a single table data model for the ski resort dataset.
 Organized and formatted the dataset for analysis in Power BI.
 Assigned correct data types and data categories to columns.
 Created DAX measures and prepared the table for visualizations.
 Enabled interactive analysis using the single table structure.
Screenshot:
<img width="586" height="479" alt="image" src="https://github.com/user-attachments/assets/19a444b6-4715-45bb-9f3e-bdb6be324b2a" />
## Calculated columns & DAX measures:
     DAX calculations were created to generate key performance indicators such as
    average price, total resorts, average slopes, and lift analysis.
    <img width="748" height="400" alt="image" src="https://github.com/user-attachments/assets/f8619add-d792-4cd0-9aa0-e985d926f929" />
    <img width="730" height="415" alt="image" src="https://github.com/user-attachments/assets/355901d9-88ab-409d-813a-c2cba9c8bffb" />

   ## Analysis and Visualizations (power BI):
# Dashboard Components:
         ## KPI Cards
The dashboard contains 6 KPI cards to display important business metrics
such as Total Resorts, Average Price, Total Slopes, Total Lift Capacity, Maximum
Highest Point, and Average Longest Run for quick performance analysis.
         ## Charts Used in Dashboard
1. Clustered Column Chart
         Used to analyze average resort pricing across different countries and
        compare pricing trends effectively.
2. Clustered Bar Chart
      Used to compare total resort distribution across countries and identify topperforming
      ski tourism regions.
 3. Pie Chart
      Used to display continent-wise percentage distribution of ski resorts for
       geographical analysis.
4. Stacked Chart
     Used to compare beginner, intermediate, and difficult slope categories across
     ski resorts.
5. Scatter Chart
      Used to analyze the relationship between lift capacity and resort operational
       performance.
6. Line Chart
       Used to identify continent-wise average pricing trends and compare regional
     pricing patterns.
## Slicers Used in Dashboard
     1. Continent Slicer
        Used to filter and analyze resort performance based on selected continents.
     2. Country Slicer
        Used to perform country-wise resort analysis and compare operational
        performance.
     3. Season Slicer
        Used to analyze seasonal trends and identify resort activity during different
       seasons.
Screenshot:
<img width="1833" height="438" alt="image" src="https://github.com/user-attachments/assets/3fde9724-7748-49e8-be4d-ef8a9a62664b" />
<img width="1833" height="438" alt="image" src="https://github.com/user-attachments/assets/f1e63654-c874-4eb9-96ce-67b4c46e622f" />
<img width="1832" height="438" alt="image" src="https://github.com/user-attachments/assets/717a211b-c050-4f6e-a6b0-a2fc3e1ccb3c" />

Key Insights:
Clustered Column Chart – Average Price by Country
<img width="919" height="514" alt="image" src="https://github.com/user-attachments/assets/1b52feae-6701-4cb4-98e9-80ed5d1a22bb" />

 Descriptive Analytics (What Happened?)
    The clustered column chart shows that countries such as
     Australia, New Zealand, and the United States maintain nearly 20–25%
    higher average resort prices compared to several other countries in the
   dataset. This indicates strong premium pricing trends and higher
   tourism value in these regions
   
    Diagnostic Analytics (Why It Happened?)
Higher average resort prices are mainly influenced by
premium tourism services, advanced resort infrastructure, better skiing
facilities, and strong international tourist demand. Countries with welldeveloped
tourism industries tend to maintain higher operational and
accommodation costs.

 Predictive Analytics (What Will Happen?)
Average resort pricing is expected to continue increasing
during peak winter tourism seasons as customer demand and
operational expenses grow. Premium ski destinations may also
experience higher international tourist attraction in the coming years.

 Prescriptive Analytics (What Should Be Done?)
Resort operators should focus on improving customer
experience, maintaining competitive pricing strategies, and offering
seasonal packages to attract more visitors. Countries with lower pricing
performance can improve resort quality and tourism promotion to
increase revenue opportunities
Clustered Bar Chart – Top Countries by Resorts
<img width="1362" height="362" alt="image" src="https://github.com/user-attachments/assets/2e6ac4f5-8fac-475e-8788-c1f94fcc7169" />
<img width="1362" height="362" alt="image" src="https://github.com/user-attachments/assets/9b23a215-60d2-4c14-9f16-49f80b550fef" />
  Descriptive Analytics (What Happened?)
The clustered bar chart highlights that Austria, France, and the
United States contribute approximately 35–40% of the total ski resort
distribution among the top-performing countries. These countries dominate
the global ski tourism market in terms of resort availability.

 Diagnostic Analytics (Why It Happened?)
The higher number of resorts is mainly due to favourable snowfall
conditions, strong tourism infrastructure, mountainous geography, and longestablished
skiing culture. These countries also receive higher tourism
investments and maintain strong seasonal visitor demand.

Predictive Analytics (What Will Happen?)
Top-performing countries are expected to continue leading ski
tourism growth due to their strong infrastructure and international tourism
popularity. Resort expansion and tourism demand may increase further in
these regions over time. 

 Prescriptive Analytics (What Should Be Done?)
Other countries should improve tourism development strategies,
increase resort investments, and strengthen marketing campaigns to improve
their global ski tourism presence. Infrastructure modernization can also help
increase visitor attraction and operational performance.

Pie Chart – Count of Resort by Continent
<img width="1371" height="397" alt="image" src="https://github.com/user-attachments/assets/b751635d-381a-4436-af76-9e0dee4d4b6c" />
<img width="1371" height="397" alt="image" src="https://github.com/user-attachments/assets/f2d5eb75-85bb-46fd-bd3a-624cbf867165" />
 Descriptive Analytics (What Happened?)
The pie chart analysis shows that Europe contributes nearly 72%
of the total ski resorts, making it the dominant continent in global ski tourism.
North America and Asia contribute comparatively smaller shares in the overall
resort distribution.

 Diagnostic Analytics (Why It Happened?)
Europe maintains a higher concentration of ski resorts because of
favourable climatic conditions, strong winter tourism demand, and developed
transportation and hospitality infrastructure. Historical popularity and tourism
investments also support resort growth in European countries.

 Predictive Analytics (What Will Happen?)
European ski tourism is expected to maintain strong dominance in
future seasons with continued tourism growth and infrastructure
improvements. Emerging regions may gradually increase their resort
presence but Europe is likely to remain the market leader.

 Prescriptive Analytics (What Should Be Done?)
Emerging tourism regions should improve resort infrastructure,
transportation facilities, and international tourism marketing to increase ski
tourism growth. Governments and operators can also invest in sustainable
tourism development strategies.

Stacked Chart – Slopes Difficulty Comparison
<img width="1331" height="434" alt="image" src="https://github.com/user-attachments/assets/ab4e5f9a-fb43-4f4a-af52-f4cccfa67189" />
<img width="1332" height="433" alt="image" src="https://github.com/user-attachments/assets/b4a7063c-a116-42d9-862d-6f79a6094a91" />
 Descriptive Analytics (What Happened?)
The stacked chart indicates that beginner and intermediate slopes
contribute around 60% of total slope availability across most ski resorts.
Difficult slopes represent a comparatively smaller percentage in overall slope
distribution.

 Diagnostic Analytics (Why It Happened?)
Most ski resorts focus on beginner and intermediate skiing facilities
to attract tourists, families, and first-time visitors. Resorts prioritize safer and
more accessible skiing experiences to increase customer participation and
tourism revenue.

 Predictive Analytics (What Will Happen?)
Demand for beginner and intermediate slopes is expected to
continue increasing due to growing tourism interest and recreational skiing
activities. Resorts may also expand training and family-friendly skiing
programs in the future.

 Prescriptive Analytics (What Should Be Done?)
Resort operators should continue improving beginner-friendly
facilities, safety measures, and skiing training services. Expanding
intermediate-level skiing infrastructure can help increase customer
satisfaction and long-term visitor retention.

Scatter Chart – Lift Capacity Analysis by Resort
<img width="1147" height="463" alt="image" src="https://github.com/user-attachments/assets/b33d8f91-4329-4ac1-bbc4-5c4f04a588ba" />
<img width="1147" height="463" alt="image" src="https://github.com/user-attachments/assets/cfb91735-5d38-4915-9841-0e8762709b17" />
 Descriptive Analytics (What Happened?)
The scatter chart analysis reveals that resorts with higher lift
capacity generally maintain approximately 30–40% greater operational
performance and slope availability compared to smaller resorts. High-capacity
resorts also show stronger visitor handling capability.

 Diagnostic Analytics (Why It Happened?)
Large resorts require advanced lift infrastructure and operational
systems to manage higher tourist volumes efficiently. Increased lift capacity
improves visitor movement, reduces waiting time, and supports larger skiing
areas.

 Predictive Analytics (What Will Happen?)
High-capacity resorts are expected to experience continuous
visitor growth and operational expansion in future tourism seasons. Resorts
with strong infrastructure may attract higher international tourism demand.

 Prescriptive Analytics (What Should Be Done?)
Resort operators should invest in advanced lift systems, visitor
management technologies, and operational efficiency improvements to
support future tourism growth. Infrastructure upgrades can improve customer
experience and increase long-term profitability.

Line Chart – Average Price by Continent
<img width="1398" height="454" alt="image" src="https://github.com/user-attachments/assets/1be8e26c-ef2b-41e6-b882-d13cecea4a58" />
<img width="1398" height="454" alt="image" src="https://github.com/user-attachments/assets/9efb5537-c858-4bea-996d-47d66540016e" />

 Descriptive Analytics (What Happened?)
The line chart shows that Oceania and North America maintain
nearly 15–20% higher average resort prices compared to Europe and Asia.
Pricing trends vary significantly across continents based on tourism demand
and resort quality. 

 Diagnostic Analytics (Why It Happened?)
Higher pricing levels are influenced by premium tourism services,
higher operational expenses, luxury accommodations, and increased visitor
demand in developed tourism regions. Seasonal demand fluctuations also
impact pricing strategies.

 Predictive Analytics (What Will Happen?)
Average resort pricing is expected to increase gradually in premium
tourism regions as operational costs and customer expectations continue
rising. Luxury ski tourism demand may also contribute to future price growth.

 Prescriptive Analytics (What Should Be Done?)
Resort operators should implement dynamic seasonal pricing
strategies, improve service quality, and introduce promotional packages to
maintain customer satisfaction and profitability. Monitoring pricing trends
regularly can support better business decision-making

Key Insights:
 Analyze ski resort performance based on continent, country, season, price
category, and lift capacity.
 Measured resort distribution, average pricing, slope counts, and lift capacity
using dashboard KPIs and charts.
 Insights were generated successfully using Power BI visualizations, slicers,
and DAX measures.
 The dashboard supports tourism analysis, pricing strategy evaluation, and
operational performance monitoring.
 Analysis focuses on seasonal resort trends and current operational
performance for timely decision-making.

Conclusion:
 The Power BI dashboard successfully transformed raw ski resort data into
meaningful business insights using interactive visualizations and analytics
techniques.
 KPI cards provided a quick overview of important metrics such as total
resorts, average price, total slopes, lift capacity, and longest run analysis.
 The clustered column chart revealed that certain countries maintain
significantly higher average resort pricing due to strong tourism demand
and premium services.
 The clustered bar chart identified Austria, France, and the United States
as leading countries in overall ski resort distribution and operational
presence.
 The pie chart analysis showed that Europe dominates global ski tourism
with the highest percentage of total resorts among all continents.
 The stacked chart highlighted that beginner and intermediate slopes
contribute the largest share of slope availability, supporting recreational
and family tourism activities.
 The scatter chart demonstrated a strong relationship between lift capacity
and resort operational performance, indicating infrastructure efficiency in
high-capacity resorts.
 The line chart showed noticeable pricing differences across continents,
with premium tourism regions maintaining higher average resort prices
Slicers and interactive filtering features improved dashboard usability and
enabled dynamic exploration of resort performance across countries and
seasons.
 Power Query and DAX calculations enhanced data transformation,
categorization, and analytical accuracy within the dashboard.
 Descriptive analytics helped summarize current resort trends and
operational performance across different geographical regions.
 Diagnostic analytics identified the reasons behind pricing variations,
tourism growth, and resort distribution patterns.
 Predictive analytics provided future expectations related to tourism
demand, pricing growth, and infrastructure expansion opportunities
               
