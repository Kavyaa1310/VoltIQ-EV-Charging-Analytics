VoltIQ EV Charging Analytics



Project Documentation



1\. Introduction



The electric vehicle industry is growing rapidly, increasing the need for efficient charging infrastructure and data driven monitoring.



VoltIQ EV Charging Analytics is a Power BI based business intelligence project developed to analyze EV charging network data. The project transforms charging related data from multiple Excel datasets into an interactive dashboard that provides insights into charging sessions, energy consumption, revenue, customers, stations, cities, charging types, payment methods, and vehicle types.



The dashboard enables users to monitor overall network performance and explore detailed business insights through interactive filters and visualizations.



2\. Project Objectives



The main objectives of the VoltIQ project are:



• Analyze the overall performance of an EV charging network.

• Monitor charging session activity.

• Analyze energy consumption across charging stations.

• Measure total and average revenue.

• Compare revenue across cities.

• Analyze charging behavior by customer and vehicle.

• Compare different charging types.

• Evaluate charging station performance.

• Analyze revenue by payment method.

• Present the analysis through an interactive Power BI dashboard.



3\. Tools and Technologies Used



Microsoft Excel



Excel files are used as the primary source of the project datasets.



Power BI



Power BI is used to:



• Import the datasets.

• Transform and prepare the data.

• Create relationships between datasets where required.

• Create calculations and measures.

• Build interactive visualizations.

• Design the final dashboard.



Power Query



Power Query is used for data preparation and transformation before creating the dashboard.



DAX



DAX is used for calculations and measures required for KPI cards and dashboard analysis.



4\. Dataset



The project contains five Excel datasets.



4.1 Charging Sessions



File: Charging\_Sessions.xlsx



This dataset contains information related to EV charging sessions, including session information, energy consumption, revenue, charging type, and payment related information. It forms the primary dataset for analyzing charging activity and revenue.



4.2 Stations



File: Stations.xlsx



This dataset contains information related to EV charging stations. It is used for station level analysis and station performance monitoring.



4.3 Vehicles



File: Vehicles.xlsx



This dataset contains vehicle related information. It is used to analyze charging activity and revenue based on different vehicle types.



4.4 Customers



File: Customers.xlsx



This dataset contains customer related information. It supports analysis of unique customers and customer charging behavior.



4.5 Data Dictionary



File: Data\_Dictionary.xlsx



The Data Dictionary provides descriptions of the available fields and helps understand the structure and meaning of the datasets.



5\. Data Preparation



The datasets were imported into Power BI and prepared for analysis.



The main data preparation activities included:



• Importing Excel datasets into Power BI.

• Checking column names and data types.

• Preparing date related fields.

• Formatting numerical fields.

• Preparing categorical fields for visualization.

• Ensuring the data could be used effectively for aggregation and analysis.

• Creating the required calculations and measures.



6\. Dashboard Design



The VoltIQ dashboard contains four main pages:



• Executive Overview

• Station Performance

• Customer and Charging Behaviour

• Revenue and Energy Analytics



The dashboard uses a consistent visual design across all pages.



Interactive slicers are provided for:



• Date

• Station

• Charging Type



These slicers allow users to dynamically explore the dashboard.



7\. Executive Overview



The Executive Overview provides a high level summary of the entire EV charging network.



KPI Cards



• Total Sessions

• Total Energy Consumed

• Total Revenue

• Unique Customers

• Active Stations



Visualizations



• Revenue by Charger Type

• Charging Session Trend

• Energy Consumed by Station

• Revenue by Location

• City Wise Performance

• Top Customer by City and Revenue

• Energy vs Revenue



Purpose



This page is designed to give decision makers a quick understanding of the overall charging network performance. It provides a combination of KPI metrics, trends, geographic information, and comparative analysis.



8\. Station Performance



The Station Performance page focuses on the performance of individual charging stations.



KPI Cards



• Total Stations

• Total Revenue

• Total Charging Sessions

• Average Revenue per Session

• Active Stations



Visualizations



• Revenue by Station and Day

• Revenue Trend

• Energy Consumption Trend

• Revenue by Vehicle Type



Purpose



This page helps identify differences in station performance and understand how revenue and energy consumption change across the network. The station and date filters can be used to analyze individual stations or specific periods.



9\. Customer and Charging Behaviour



The Customer and Charging Behaviour page focuses on customer activity and charging behavior.



KPI Cards



• Unique Customers

• Total Charging Sessions

• Average Revenue per Session

• Vehicle Count

• Active Stations



Visualizations



• Energy Consumed by Station

• Revenue by City

• Charging Duration by City



Purpose



This page provides insights into customer activity, charging patterns, and geographic differences in charging behavior. It can help identify locations with higher customer activity and understand charging duration across different cities.



10\. Revenue and Energy Analytics



The Revenue and Energy Analytics page provides detailed analysis of financial and energy related performance.



KPI Cards



• Total Revenue

• Total Energy Consumed

• Average Revenue per Session

• Average Energy per Session

• Average Energy Rate



Visualizations



• Revenue Trend

• Energy Consumption Trend

• Energy by Charging Type

• Revenue by City

• Revenue by Payment Method



Purpose



This page helps analyze the relationship between revenue and energy consumption. It also provides comparisons between charging types, cities, and payment methods.



11\. Key Performance Indicators



The dashboard uses KPI cards to provide quick access to important business metrics.



Total Sessions



Represents the total number of charging sessions recorded in the dataset.



Total Energy Consumed



Represents the total amount of energy consumed through charging sessions.



Total Revenue



Represents the total revenue generated through charging sessions.



Unique Customers



Represents the number of unique customers using the charging network.



Active Stations



Represents the number of active charging stations.



Average Revenue per Session



Represents the average revenue generated from a charging session.



Average Energy per Session



Represents the average energy consumed during a charging session.



Average Energy Rate



Represents the average energy rate calculated from the available charging data.



12\. Business Analysis



VoltIQ provides several areas of business analysis.



Revenue Analysis



Revenue can be analyzed by:



• City

• Charging Type

• Payment Method

• Vehicle Type

• Station



This helps identify high performing locations and revenue sources.



Energy Analysis



Energy consumption can be analyzed by:



• Station

• Charging Type

• Time

• City



This helps understand energy usage patterns across the charging network.



Customer Analysis



Customer related analysis includes:



• Unique Customers

• Charging Sessions

• Vehicle Count

• Charging Duration

• City Wise Customer Activity



Station Analysis



Station performance can be evaluated using:



• Revenue

• Charging Sessions

• Energy Consumption

• Daily Performance

• Vehicle Type Contribution



13\. Interactive Dashboard Features



The dashboard provides interactive filtering using slicers.



Date Filter



Allows users to analyze data for a selected date or period.



Station Filter



Allows users to focus on a particular charging station.



Charging Type Filter



Allows users to compare different charging types.



The visualizations update dynamically when filters are applied.



14\. Dashboard Benefits



The VoltIQ dashboard provides the following benefits:



• Provides a centralized view of EV charging performance.

• Makes large datasets easier to understand.

• Helps compare charging stations.

• Supports revenue analysis.

• Helps monitor energy consumption.

• Provides customer behavior insights.

• Enables interactive exploration of business data.

• Supports data driven decision making.



15\. Project Structure



VoltIQ EV Charging Analytics



Dataset



• Charging\_Sessions.xlsx

• Stations.xlsx

• Vehicles.xlsx

• Customers.xlsx

• Data\_Dictionary.xlsx



Documentation



• README.md

• Project\_Documentation.pdf



PowerBI



• VoltIQ\_EV\_Charging\_Analytics.pbix



Screenshots



• 01\_Executive\_Overview.png

• 02\_Station\_Performance.png

• 03\_Customer\_Charging\_Behaviour.png

• 04\_Revenue\_Energy\_Analytics.png



16\. Conclusion



VoltIQ EV Charging Analytics demonstrates the use of Power BI to convert EV charging data into an interactive business intelligence dashboard.



The project combines multiple datasets and presents information through KPI cards, charts, tables, trends, and geographic analysis.



The four dashboard pages provide a complete view of:



• Overall charging network performance

• Station performance

• Customer and charging behavior

• Revenue and energy analytics



The project demonstrates practical skills in data preparation, data analysis, Power BI visualization, dashboard design, and business intelligence reporting.



Project Summary



Project Name: VoltIQ EV Charging Analytics



Domain: Electric Vehicle Charging



Category: Data Analytics and Business Intelligence



Primary Tool: Microsoft Power BI



Data Source: Microsoft Excel



Dashboard Pages: 4



Dataset Files: 5



Output: Interactive EV Charging Analytics Dashboard



