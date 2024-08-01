# Capstone-Group-4
Aryan Zodge, Benjamin Combs. Isabella Recine, Kaitlyn Borski

### Overview
In this capstone project, you will work with High Volume For-Hire Vehicle (HVFHV) data, Yellow Taxi Data, and Green Taxi Data. Your objective is to extract this data from AWS S3 (Raw), perform necessary transformations, and load it into a Conformed S3 bucket, and finally into a Transformed S3 bucket before importing it into Snowflake for final analysis using Tableau or Thoughtspot. You will leverage various AWS services and tools, including AWS Lambda, Python/Jupyter Notebook, Databricks/PySpark, AWS Glue Studio or AWS Glue Databrew, AWS Glue Crawler and Catalog, AWS Athena, Snowflake, and Tableau.

Before beginning the project, you must select a specific use-case to focus on. You will assume the role of a consultant, using a data-driven approach to highlight your findings and provide actionable recommendations where appropriate. Your task is to employ your Data Engineering skills to transform the data from its RAW state into a format that facilitates in-depth analysis.

You will work with the provided datasets, which include data dictionary files and additional lookup tables. Additionally, you are encouraged to incorporate other data sources to enrich the existing data, thereby enhancing your analysis and providing deeper insights. This project is designed to be case study-driven, allowing you to explore real-world scenarios and solve tangible problems using data engineering techniques.

### Use Cases
**Optimizing Fleet Management and Safety**
 - Improve safety and efficiency by analyzing taxi demand locations and accident hotspots.
 
**Implementation**
- Taxi Demand: use taxi data to identify areas of high demand and peak times
- Dynamic Pricing: adjust prices based on demand during peak hours
- Identify High-Risk Areas: analyze crash data in areas of high taxi demand
 
**Business Benefits**
- Increased revenue with dynamic pricing and driver allocation
- Increased customer satisfaction?

#### Crash Data Source: 
```
s3://capstone-techcatalyst-raw/group_4_other/Motor_Vehicle_Collisions_-_Crashes_20240731.csv
```
#### Taxi Zone Lookup:
```
s3://capstone-techcatalyst-raw/other/taxi_zone_lookup.csv
```
