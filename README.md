# ETL_project_yellow_tripdata
Introduction
This work is about creating a data pipeline popularly known as ETL. A dataset is obtained(yellow_tripdata_2016-02.csv) which consists of 11,382,050 rows in total. One million rows are extracted, transformed and loaded into a postre SQL database.

Project Purpose
This project focuses on ingesting 1 million rows of data from the NYC Yellow Taxi dataset provided(yellow_tripdata_2016-02.csv speicfically). The goal is to create a robust data pipeline that can effciently handle and store the dataset for subsequent analysis.

Execution of codes
Table1:
operations_and_performance
1. How many trips were recorded in the dataset?
2. What is the average trip distance for all trips?
3. Which Vendor has the highest number of trips?
4. Which Vendor has the lowest number of trips? 
5. What is the average passenger count per trip?

The above table carries the below column headings
ingestion_date | total_trips | avg_trip_distance |highest_trip_vendor | lowest_trip_vendor | avg_passenger_count

Table2:
customer_demographics_and_preferences
1. What is the average trip amount given by passengers?
2. What is the average trip distance by passengers?
3. How many trips were ?agged as 'store and forward'?
4. How many trips were shared rides (passenger count > 1)?
ingestion_date | avg_tip_amount |  avg_trip_distance_by_passenger | store_and_forward_trips |shared_ride_count 

Table3:
financial_performance
1. What is the average fare amount per trip?
2. How much revenue was generated from tolls and 
surcharges combined?
3. What is the average total amount paid by passengers?
ingestion_date | avg_fare_amount | tolls_and_surcharges_revenue | avg_total_amount 

Creating Reporting Tables
Codes were executed to obtain th following:

Cleaning up with Re-usable Function
Code were executed to achieve the folowing:
i. Succesful transormation of the data
ii. Successful updating of the nyc_reports table


