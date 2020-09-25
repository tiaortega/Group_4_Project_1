# Group_4_Project_1

## Impact of COVID-19 on Texas Workforce

**Team Members:** Tia Anderson-Ortega, Josh Bond, Janette Chairez, Anthony Goins, Krishna Pulipaka

**Link to GitHub Repository:** https://github.com/tiaortega/Group_4_Project_1

### Repository Structure and Navigation

1. Resources Folder contains CSV's from all url queries

2. Output_data Folder contains the DataFrames merged and cleaned for Data Visualization

3. Images Folder contains all plots graphs and charts

4. Execution files, work through in order: 

    • Add gkey and api_key to config.py

 **Data Puller**- Queries for BLS, TLM, and COVID-19 Data
     
    CSV exports to Resources Folder
        * Texas Labor Market CES Data
        * Texas Labor Market Indicators
        * Texas Labor Market LAUS Data
        * covid_tx_df
        * covid_ny_df
        * covid_all_df
        * Houston_data
        * Men_unemployed
        * Women_unemployed
        * Total_Teen

 **BLS_DFs_Plts**- BLS data merging and analysis
    
    Imports
        * Houston_data
        * Men_unemployed
        * Women_unemployed
        * Total_Teen 
    
    Exports
        * MF_Teen_unempl
        * Hou_Tot_Claims
        * NY_Tot_Claims
        * Statitistics Unemployment Data
        * Hou_Claims_MFage

 **Statistical Analysis of Covid Data**
    
    Imports
        * covid_tx_df
        * covid_ny_df
        * covid_all_df        * 
    
    Exports
        * % positive tests by month
        * TX August Daily % Positives
        * TX vs NY % Posititves Boxplot June to Sept
        * TX vs NY % Posititves Boxplot
        * TX vs NY % Positives Monthly Averages
        * TX vs NY % Posititves Frequency
        * TX vs NY Daily % Postive June to Sept
        * TX vs NY Daily Testing Totals Frequency
        * TX vs NY June to Sept % Posititves Frequency
        * TX vs NY% Positive June to Sept
        * TX vs NY Totals Boxplot     
 
 **Texas vs New York in Positive Covid-19 Testing by Month bar chart**
    
    Imports
        * % positive tests by month
    
    Exports 
        * TXvsNY
   
**ProjectDataJanette**
    
    Imports
        * % Women Unemployed
        * % Men Unemployed

    Exports
        * Texas Male & Female Unemployment vs. % Positives
        * Reduced TX % Unemployment vs. Covid % Positive
        * Texas Adolescent Positives vs. Women Unemployment
        * Texas Adolescent Positives vs. Men Unemployement 
        * % positive tests and unemployment   
      
 **Group4 Project 1Notebook_geomap**
    
    Imports
        * CountyLatLong
        * TXCountiesUnemployRateChanges
        * Gmaps

    Exports
        * Heatmap_UnemploymentRatesPerCounty
        * TX County Markers
    
 
    
 **Annual_Change_by_industry**

    Imports 
        * Texas Labor Market CES Data

    Exports
        * Unemp_by_industry_month_year
        * Annual_Change_by_Industry



### Project Description/Outline: 

    • Analysis of Job Turnover and Separation because of COVID-19 by using Texas Market Data, Covid Tracking Data and Bureau of Labor Statistics.

    • United States and Texas Unemployment Rate Comparison by providing geospatial visualizations specifically delta change per County between July 2019 and July 2020 • Texas Labor Market Analysis for Percent Women and Men COVID Positive Tests with a Line Graph over April 2020 to August 2020 • Total claims for Houston between Jan 2019 to July 2020 with a Line Graph

    • Percent of Unemployment Rate by Men, Women and Teenagers with a Line Graph • Bar graph comparison of Positive Tests Per Month for Texas and New York • Comparing Industry by Industry Annual % Change of Unemployment Rate via Bar Graph • Statistical Analysis

### Research Questions and Answers:

 **Make an Assumption–** 
    1. Unemployment Rates and Claims are directly correlated to COVID-19 cases/deaths (Comparing July 2019 and July 2020 data)

    2. Have any specific industries affected more than others?
    
    3. Which age-group is most impacted?
    
    4. Compare TX and NY and perform t-tests, calculate p-value etc.

 **Data Sets to be Used:** 

     *   Patient COVID-19 Test Results Api.tracking.com 

     *  Daily State (TX & NY) Bureau Labor Statistics (BLS) Data 

     *  (Free API) – version 2 Texas Labor Market Labor Data 

 **Rough Breakdown of Tasks:** 

    • Creating the GitHub – Tia – Done 
    • Obtain data sets from the hospital – Janette 
    • Clean up COVID-19 API – Krishna 
    • Clean up BLS API – Anthony 
    • Create MatPlotLib Visualizations: 
        o (2) Geo Map Visualizations – Krishna 
        o (3) Line Graphs – Date/Time – Anthony & Janette 
        o (2) Bar Graphs – Tia 
        o (2) Scatter Plot – Josh 
    • Statistic Measures and Box Plot – Josh 
    • Write Up/Presentation (Power Point and Readme) – ALL

### Conclusions:

    For the months of May through August their is a very strong correlation between between COVID 19 cases and Texas County unemployment data. May being the earliest due to volume of testing being statistically relevant, and August being the latest month for which we had unemployment data.

    We assume that positive COVID 19 cases will go down as parents that were laid off stayed home, to determine would require finding the derivative of the slope over time. From general observation this is the case leading to the conclusion that the less people unemployed led to a lower change in decreasing % positives over time.

    There were more women suffered greater % job losses than men,
    however, teens 16-19 were the highest affected age group. This was the case for both years, leading to the conclusion that the normal state of unemployment spreads from high to low are teens, adult women, adult men.


    There were examples of unemployment % increases, decreases, and stagnation. I would conclude that the effect of unemployment percentage pre and post covid is mostly in magnitude which could be determined by year over comparisons.

    Couriers and Messengers industry has positive growth and support activities for Mining (suppliers, transportation and materials)


