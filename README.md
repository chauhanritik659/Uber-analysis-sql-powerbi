# Uber-analysis-sql-powerbi


## Table of Contents
- [Uber Ride Data Analysis Project](#uber-ride-data-analysis-project)
  - [Project Overview](#project-overview)
  - [Business Problem](#business-problem)
  - [Objective](#objective)
  - [Dataset Description](#dataset-description)
    - [Key Columns](#key-columns)
  - [Tools and Technologies](#tools-and-technologies)
  - [Data Analysis Using SQL](#data-analysis-using-sql)
  - [Power BI Dashboard Analysis](#power-bi-dashboard-analysis)
  - [Key Insights](#key-insights)
  - [Business Recommendations](#business-recommendations)
  - [How to Run This Project](#how-to-run-this-project)
  - [Project Folder Structure](#project-folder-structure)
  - [Power BI Dashboard Screenshot](#power-bi-dashboard-screenshot)
  - [Conclusion](#conclusion)
  - [Author](#author)

## Project Overview
This project analyzes Uber ride booking data for July 2025 to generate actionable business insights related to ride trends, booking performance, cancellations, revenue distribution, and customer behavior. The analysis was performed using SQL and Power BI to support data-driven decision-making.

## Business Problem
Ride-hailing platforms handle large volumes of booking data daily, but raw data alone does not provide meaningful insights. Without proper analysis, it becomes difficult to identify peak demand periods, understand cancellation reasons, evaluate vehicle performance, and improve customer satisfaction.

## Objective
The objective of this project is to:
- Analyze ride success and cancellation patterns
- Identify peak booking periods
- Evaluate vehicle category performance
- Understand customer and driver ratings
- Analyze revenue and payment method trends
- Support business decisions using data insights

## Dataset Description
The dataset contains ride booking–level transactional data for July 2025.

### Key Columns
- Booking_ID  
- Booking_Status  
- Booking_Value  
- Customer_ID  
- Driver_ID  
- Pickup_Location  
- Drop_Location  
- Ride_Distance  
- Ride_Time  
- Vehicle_Type  
- Payment_Method  
- Customer_Rating  
- Driver_Rating  

## Tools and Technologies
- PostgreSQL for data analysis using SQL  
- Power BI for data visualization and dashboards  
- Microsoft Excel for initial data review  

## Data Analysis Using SQL

### Retrieve All Successful Bookings
```sql
SELECT *
FROM rides_data
WHERE Booking_Status = 'Success';

