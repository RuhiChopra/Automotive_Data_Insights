# Automotive Data Insights: SQL Analysis on Used Cars

This project provides a comprehensive analysis of automotive industry trends using real-world, multi-year car sales data and advanced SQL queries. The goal is to uncover actionable insights on pricing, mileage, and performance metrics for a wide range of car models.

---

## Dataset Overview

- **File:** `Automotive_Data_Insights.csv`  
- **Attributes:**  
  - `Name`: Car model  
  - `year`: Year of sale  
  - `sellingprice`: Selling price (currency unit unspecified)  
  - `kmdriven`: Kilometers driven  
  - `fuel`: Fuel type (Petrol, Diesel, Electric, etc.)  
  - `sellertype`: Seller type (Individual, Dealer)  
  - `transmission`: Transmission type (Manual, Automatic)  
  - `owner`: Ownership status (First, Second, Third Owner, etc.)  
  - `mileage`: Mileage (kmpl or km/kg for CNG)  
  - `engine`: Engine capacity (CC)  
  - `maxpower`: Maximum power (bhp)  
  - `torque`: Torque (Nm)  
  - `seats`: Number of seats  
This dataset contains thousands of rows spanning dozens of major automotive brands and variants, making it suitable for in-depth data mining and statistical analysis.

---

## Analysis Techniques

- **File:** `Automotive_Data_Insights.sql`
- The SQL script demonstrates:
  - Calculation of average selling price by fuel, ownership, and transmission type.
  - Ranking car models by average mileage for cars with over five seats.
  - Identifying models with large price variations.
  - Filtering cars sold above average price and below average mileage.
  - Cumulative and moving averages for selling prices across years.
  - Detecting models with selling prices close to the average.
  - Exponential moving average calculations (smoothing factor: 0.2).
  - Identification of price drops vs. previous year.
  - Aggregation of highest total mileage by transmission type.
  - Year-on-year average selling price for top-performing models.

---

## Example Usage

1. **Load the CSV dataset into your database or analysis environment.**
2. **Run the SQL queries to visualize trends.**
    - Customize the WHERE and GROUP BY clauses for brand-specific or temporal analysis.
3. **Perform additional machine learning or dashboarding projects using the rich, well-structured automotive data.**

---

## Requirements

- Any SQL-compatible environment (MySQL, PostgreSQL, SQLite) or data platform supporting standard analytical functions.

---

## Project Structure

```
/
├── Automotive_Data_Insights.csv
├── Automotive_Data_Insights.sql
└── README.md                # This file
```

---

## Citation

Data sourced from real-world automotive sales and engineering records. SQL queries crafted to model practical business intelligence use cases.
