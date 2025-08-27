
# 🚖 Ola Data Analysis | SQL, Excel, Power BI

## 📌 Project Overview

This project analyzes Ola Cab Ride Data to uncover insights about booking patterns, cancellations, revenue, and overall customer experience. Using SQL for data preparation, Excel for exploratory checks, and Power BI for visualization, the project provides actionable insights for decision-making.

## 🛠 Tools & Technologies

**SQL** → Data cleaning & queries

**Excel** → Exploratory analysis & validation

**Power BI** → Interactive dashboards with KPIs

## 📂 Dataset Columns

Date, Time, Booking_ID

Booking_Status (Success / Cancelled by Driver / Customer / Not Found)

Vehicle Type (Auto, Prime Sedan, Mini, Bike, SUV, etc.)

Pickup & Drop Location

Ride Distance, Booking Value

Driver & Customer Ratings

Payment Method

## 📊 Dashboard Features

**Overall View:** Total bookings (20,407), Total value (7M), Ride status breakdown, Ride trends over time.

**Vehicle Type:** Top 5 vehicle categories by ride distance.

**Revenue:** Revenue by payment method, Top 5 customers by spend.

**Cancellations:** Breakdown of driver vs. customer cancellations with reasons.

**Ratings:** Average driver & customer ratings by vehicle type.

## 📈 Key Insights (from Data + Dashboard)

✅ **62% rides successful** → Majority of customers served.

❌ **28% cancellations** → Significant losses due to driver & customer behavior.

💰 **Total booking value:** 7M in July 2024 → Strong revenue potential.

🚖 **Prime rides** contribute most to revenue, while Autos/Bikes drive higher ride volumes.

⭐ **Ratings distribution** → Average customer satisfaction varies by vehicle type.

📅 **Higher demand on weekends & match days** → Indicates event-driven spikes.

## 📑 Steps Followed

### 1.  Data Preparation (SQL) →
  ➡️Removed duplicates & missing values
  
  ➡️Standardized booking status categories

  ➡️Aggregated total rides & revenue

### 2. Exploratory Analysis (Excel) →
  ➡️Created pivot tables for cancellation trends

  ➡️Checked booking volume distribution

### 3. Data Modeling (Power BI) →

  ➡️Built relationships between ride, customer, and driver tables

  ➡️Created DAX measures for KPIs (Total Bookings, Revenue, Success Rate, Cancellation Rate)

### 3. Dashboard Creation (Power BI) →

  ➡️Added KPIs, slicers, pie chart, line chart

  ➡️Designed navigation for multiple analysis views

## 📷 Dashboard Preview
<img width="1589" height="896" alt="Ola SanpShot" src="https://github.com/user-attachments/assets/d890e055-8b77-4422-a0a1-1e7e4f43555f" />

## 🚀 How to Use

**1.Clone the repository or download files.**

**2.Run SQL scripts to clean and prepare raw data.**

**3.Validate summary stats in Excel.**

**4.Open ola_dashboard.pbix in Power BI to interact with dashboard.**
