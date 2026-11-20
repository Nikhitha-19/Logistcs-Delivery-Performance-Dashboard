# Logistics & Delivery Performance Analysis | Power BI

## Project Overview

This project focuses on analyzing logistics and delivery operations using Microsoft Power BI. It provides insights into shipment performance, delivery delays, shipping partner performance, warehouse distribution, and regional delivery trends.

The main objective is to monitor delivery efficiency, identify delay patterns, and support data-driven business decisions through interactive dashboards.

## Objectives

- Analyze overall shipment and delivery performance.
- Monitor on-time and delayed deliveries.
- Identify cities and regions experiencing higher delivery delays.
- Compare delivery partner performance.
- Analyze warehouse-wise shipment distribution.
- Understand monthly shipment trends.
- Explore the relationship between delivery distance and delivery time.
- Identify areas for improving logistics operations.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Calculated columns, measures, and KPI calculations.
- **Data Modeling** – Relationships and date-based analysis.

## Dataset

The project uses a simulated logistics dataset containing **8,000 shipment records**.

The dataset includes the following columns:

- Order ID and Customer ID
- Order Date, Dispatch Date, and Delivery Date
- Expected Delivery Date
- Product Category
- Warehouse
- Region, State, and City
- Delivery Partner
- Shipping Mode
- Distance (KM)
- Shipping Cost
- Order Value
- Order Status

*Note: The dataset is synthetic and created for educational and portfolio purposes. It does not represent actual company transactions.*

## Data Preparation

Data preparation was performed using Power Query in Power BI.

The following steps were carried out:

- Checked and handled duplicate records.
- Identified and handled missing values.
- Changed columns to appropriate data types.
- Standardized text values using Trim and Clean.
- Created a State column by mapping cities to their corresponding states.
- Created calculated columns for Delivery Days, Delay Days, Delivery Performance, and Processing Days.
- Created a Date Table for time-based analysis.
- Established relationships between tables.
- Created DAX measures for KPIs and business metrics.

## Calculated DAX
<img width="491" height="542" alt="image" src="https://github.com/user-attachments/assets/61e8a8bb-4a7b-47b8-a3de-df3688b357c0" />
<img width="520" height="561" alt="image" src="https://github.com/user-attachments/assets/c35f8e13-fede-4104-b850-4a026addc3df" />


## Calculated Columns
<img width="584" height="637" alt="image" src="https://github.com/user-attachments/assets/1ab0e12b-8ed5-49a6-888f-613f5ee45a9a" />
<img width="316" height="131" alt="image" src="https://github.com/user-attachments/assets/d3f1e9a2-cd70-48c5-8045-7fc372d62dca" />

## Creating Date Table
<img width="365" height="209" alt="image" src="https://github.com/user-attachments/assets/3a3c1770-5663-41e3-88ca-62c86424e17e" />


## Dashboard Features

The project consists of **two interactive dashboard pages**.

### Dashboard 1: Delivery Performance & Delay Analysis

Provides an overview of shipment performance, delivery delays, and regional delivery patterns.

### - KPI Cards

- Total Shipments
- Average Delivery Days
- On-Time Delivery %
- Delivery Delay %
- Total Order Value
- Average Processing Days

### - Visualizations

- **Monthly Orders:** Analyzes monthly shipment trends.
- **Shipment Delays Breakdown:** Compares on-time and delayed shipments.
- **Delayed Deliveries by Product Category:** Identifies product categories with higher delivery delays.
- **Top Cities with Delays:** Highlights cities with the highest number of delayed deliveries.
- **Zone-wise Analysis:** Displays regional shipment distribution.
- **Delay Analysis by Partner:** Compares delivery partner shipment and delay distribution.

**Interactive Filters:**
- Month
- Year

---

### Dashboard 2: Shipment Delivery Insights

Provides a detailed analysis of delivery partners, warehouse distribution, shipment volume, and delivery duration.

### - KPI Cards

- Total Delayed Deliveries
- Total On-Time Deliveries
- Number of Delivery Partners
- Total Customers

### - Visualizations

- **Warehouse-wise Shipment:** Analyzes shipment distribution across warehouses.
- **Delivery Partner Performance Matrix:** Compares total orders, on-time delivery percentage, average delivery days, and delivery delay percentage.
- **Distance vs Average Delivery Days:** Uses a scatter plot to explore the relationship between delivery distance and delivery duration.
- **Shipment Volume & Delivery Time Trends:** Compares total orders and average delivery days over time.
- **City-wise Deliveries:** Visualizes delivery distribution across cities.

**Interactive Filters:**
- Quarter
- Year
- Warehouse
- State

**Additional Features:**
- Reset Filters button
- Dashboard page navigation
- Interactive slicers and visual filtering

## 📈 Key Insights

The dashboard enables analysis of the following business areas:

- Overall shipment performance and on-time delivery trends.
- Distribution of delayed and on-time shipments.
- Product categories and cities experiencing delivery delays.
- Regional differences in delivery performance.
- Shipment volume and delivery partner distribution.
- Warehouse-wise shipment patterns.
- Relationship between delivery distance and delivery duration.
- Monthly shipment volume and average delivery time trends.

## 💼 Business Recommendations

Based on the analysis, logistics management can consider the following actions:

- Monitor regions and cities with higher delivery delays.
- Review delivery partner performance regularly.
- Investigate product categories contributing to delivery delays.
- Optimize warehouse operations based on shipment distribution.
- Evaluate shipping modes to improve delivery efficiency.
- Monitor delivery distance and duration to identify potential logistical challenges.
- Track on-time delivery performance through regular KPI monitoring.

## Dashboard Preview

### Dashboard 1 – Delivery Performance & Delay Analysis
<img width="1224" height="699" alt="Dashboard-1" src="https://github.com/user-attachments/assets/c3df78ab-33f6-4660-9b87-de4d6d170056" />

### Dashboard 2 – Shipment Delivery Insights
<img width="1265" height="726" alt="Shipment Delivery Insights" src="https://github.com/user-attachments/assets/9d6b795b-a0ce-455f-a6cd-e7254551b3da" />


## Skills Demonstrated

- Data Cleaning and Transformation
- Power Query
- DAX Calculations
- Data Modeling
- KPI Development
- Interactive Dashboard Development
- Data Visualization
- Business Analysis
- Analytical Thinking
- Data-Driven Decision Making
