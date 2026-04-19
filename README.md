# Hospitality Revenue Insights - Atliq Grands

## Project Overview
This project provides a comprehensive revenue analysis for **Atliq Grands**, a luxury hotel chain. Facing a decline in market share and revenue due to strategic moves by competitors and ineffective decision-making, the management decided to implement "Business and Data Intelligence" to regain their position in the market. 

The goal was to build a dashboard that tracks key metrics and provides actionable insights across different cities, properties, and booking platforms.

## Tech Stack
* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Power Query** (Data Cleaning & Transformation)

## Key Metrics (KPIs) Explained
To analyze the hospitality business, the following key metrics were developed:
* **RevPAR (Revenue Per Available Room):** Measures the revenue generated per available room. It is the primary metric to evaluate financial performance.
* **ADR (Average Daily Rate):** The average price paid for a room per day.
* **Occupancy %:** The ratio of occupied rooms to total available rooms.
* **Realization %:** The percentage of successful "checked out" bookings versus total bookings (accounting for cancellations).
* **DSRN (Daily Sellable Room Nights):** Average number of rooms available for sale per day.

## Dataset Description
The analysis is based on the following data structures:
* `dim_hotels`: Metadata about properties, categories (Luxury/Business), and cities (Mumbai, Delhi, Hyderabad, Bangalore).
* `dim_date`: Date table for time-series analysis (month-over-month, week-over-week).
* `dim_rooms`: Room classifications (Standard, Elite, Premium, Presidential).
* `fact_bookings`: Transactional records including revenue generated, revenue realized, and customer ratings.
* `fact_aggregated_bookings`: Aggregated daily capacity and successful bookings per property.

## Key Insights (Sample)
* **City Performance:** Mumbai leads in revenue generation, while Delhi maintains the highest occupancy rates.
* **Category Contribution:** The 'Luxury' category accounts for roughly 60% of total revenue.
* **Platform Efficiency:** Online platforms show higher booking volumes, but 'Direct Offline' remains a critical touchpoint for specific segments.
* **Temporal Trends:** Weekends show a significant spike in Occupancy and Revenue, suggesting a strong leisure travel influence.

## How to Use This Repository
1. **Data:** The raw CSV files are located in the `/Data` directory.
2. **Report:** The `.pbix` file containing the interactive dashboard is in the `/Reports` directory.
3. **Software:** You will need [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to open and interact with the report.

---
*Created as a strategic data project to solve revenue leakage and optimize hotel management operations.*
