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
  - [Project Folder Structure](#project-folder-structure)
  - [Power BI Dashboard Screenshot](#power-bi-dashboard-screenshot)
      - ![Overview](Screenshots/overview.png)
      - ![Revenue](Screenshots/revenue.png)
      -![Cancellations](Screenshots/cancellations.png)
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

## Data Analysis Using SQL

### Retrieve All Successful Bookings
This analysis focuses on identifying all rides that were completed successfully. By isolating successful bookings, the business can accurately measure completed ride volume, revenue generation, and service efficiency without interference from cancelled or failed rides.

### Average Ride Distance by Vehicle Type
This analysis calculates the average distance traveled for each vehicle category. It helps understand customer travel behavior and reveals which vehicle types are generally preferred for longer or shorter trips. These insights support better vehicle allocation and pricing strategies.

### Cancellation Analysis by Customers
This analysis measures the total number of rides cancelled by customers. Understanding customer-driven cancellations helps identify pain points such as long wait times, pricing issues, or poor service experience, allowing the business to take corrective action.

### Top 5 Customers by Number of Rides
This analysis identifies the most frequent customers based on total ride bookings. Recognizing high-usage customers enables the business to design loyalty programs, targeted offers, and retention strategies for valuable users.

### Maximum and Minimum Driver Ratings for Prime Sedan
This analysis examines the highest and lowest driver ratings within the Prime Sedan category. It helps assess service quality, identify performance gaps, and maintain consistent customer experience across premium vehicle offerings.

## Power BI Dashboard Analysis
Power BI dashboards were created to visualize ride trends, booking performance, revenue distribution, and customer behavior using interactive visuals.

## Key Insights
- Ride volume was highest during weekends  
- Certain vehicle types showed higher booking success rates  
- Lower ratings were frequently associated with cancelled rides  
- Digital payment methods dominated overall transactions  

## Business Recommendations
- Improve driver availability during peak demand periods  
- Reduce ride cancellations through better driver-customer matching  
- Promote high-performing vehicle categories  
- Encourage drivers to maintain higher ratings

## Project Folder Structure

Uber-Data-Analysis/
-├── Data/
-│   └── uber_rides_data.csv
-├── SQL/
-│   └── uber_analysis_queries.sql
-├── PowerBI/
-│   └── Uber_Dashboard.pbix
-├── Screenshots/
-│   └── powerbi_dashboard.png
-├── Report/
-│   └── Uber_Data_Analysis_Report.pdf
-└── README.md
