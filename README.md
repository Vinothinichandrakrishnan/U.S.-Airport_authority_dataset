# Airport Data Analysis Project: 2018 U.S. Dataset

This project aims to analyze flight data from U.S. airports for the year 2018. The objective is to improve operational efficiency, optimize scheduling, and enhance decision-making for airport authorities through data-driven insights.

## DATASET

- Source: Kaggle
```sh
https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018?select=2018.csv
```
- Time Frame: January 1, 2018, to December 31, 2018.
- Flight Table: Contains data on individual flights, including departure/arrival times, delays, and cancellations.
- Airport Table: Information about airport codes, names, and cities is provided.
- Carrier Table: Lists airline carrier codes and names.

## PROJECT STRUCTURE

### **Data Collection**

Source: The dataset was collected from Kaggle for 2018, covering flights across various U.S. airports.

### **Data Cleaning**

- Duplicate Removal: Checked for and removed any duplicate records.
- Error Correction: Identified and corrected errors in time data, ensuring accurate flight scheduling and performance metrics.
- Time Formatting: Converted various time fields (e.g., departure/arrival times) to a consistent hh:mm:ss format and adjusted for overnight flights.
- Aggregation: Grouped and aggregated data by periods, carriers, and airports for summary statistics.
- Calculated Columns: Created additional columns to handle specific scenarios like diverted and cancelled flights.

### **Data Transformation**

- Data Relationships: Established relationships between flight, airport, and carrier datasets for integrated analysis.
- DAX Calculations: Created calculated columns and measures for metrics such as total delays, on-time performance, and ground processing times.

### **Data Analysis**

- Flight Volume Trends: Analyzed flight volumes over time to identify peak periods and potential bottlenecks.
- Delay Causes: Investigated the reasons behind flight delays, categorized by carriers, airports, and weather conditions.
- Carrier Performance: Assessed carrier performance metrics, focusing on on-time performance and delay rates.

### **Data Interpretation - Power BI**

- Flight Volumes & Performance Analysis: Includes trends over time, total delays, on-time performance, and ground processing times.
- Carrier Analysis: Highlights carrier performance regarding delays, cancellations, and on-time performance.
- Delay Cause Analysis: Breaks down delays by cause, providing insights into the most significant contributors to flight disruptions.
- Airport Analysis: Focuses on airport performance, including delay rates, on-time performance, and cancellation/diversion rates.
- Flights Path: Visualizes flight paths and volumes using geographical maps.

### **Key Insights**

- November 2018 had the highest flight volume and delays.
- Southwest Airlines had significant total delays and cancellations, while Endeavor Airlines led in on-time performance.
- Hartsfield-Jackson Atlanta International Airport experienced the highest carrier delays.

## FILES INCLUDED

- Data Cleaning Scripts: DAX Formulas used for data cleaning and preprocessing.
- DAX Formulas: Key DAX formulas used in Power BI for calculated columns and measures.
- Power BI Dashboards: Exported .pbix file containing all the interactive dashboards.

## CONCLUSION

This project offers a comprehensive analysis of 2018 U.S. airport data, providing insights into flight operations, delays, and performance metrics. The interactive Power BI dashboards serve as powerful tools for decision-makers in the aviation industry.



