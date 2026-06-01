# 🚖 OLA Ride Booking Analysis | SQL & Power BI

## 📌 Project Overview

This project analyzes OLA ride-booking data using SQL and Power BI to uncover insights related to ride volume, booking success, cancellations, customer behavior, driver performance, and revenue trends.

The objective is to transform raw ride-booking data into actionable business insights that can help improve operational efficiency and customer experience.

---

## 🛠️ Tools & Technologies

* SQL (MySQL)
* Power BI
* Microsoft Excel
* Data Cleaning
* Data Visualization

---

## 📂 Dataset

The dataset contains ride booking information including:

* Booking ID
* Customer ID
* Vehicle Type
* Booking Status
* Ride Distance
* Payment Method
* Customer Ratings
* Driver Ratings
* Booking Value
* Cancellation Reasons

---

## 🎯 Business Objectives

* Analyze booking success and cancellation trends
* Identify top-performing customers
* Evaluate vehicle type performance
* Measure revenue contribution by payment methods
* Assess customer and driver satisfaction
* Generate actionable business recommendations

---

## 📊 Dashboard Preview

![Dashboard 1](./images/dashboard1.png)

---

## 🔍 Key Insights

### Booking Analysis

* Identified successful and cancelled ride patterns.
* Analyzed customer-side and driver-side cancellations.

### Customer Analysis

* Identified top customers based on booking frequency and revenue contribution.
* Evaluated customer satisfaction through ratings.

### Driver Performance

* Analyzed driver ratings across vehicle categories.
* Identified service quality trends.

### Revenue Analysis

* Evaluated revenue generated across different payment methods.
* Measured booking value contribution by ride category.

### Vehicle Analysis

* Compared average ride distance across vehicle types.
* Identified the most utilized vehicle categories.

---

## 💻 SQL Skills Demonstrated

* Data Filtering
* Aggregations
* GROUP BY
* ORDER BY
* Views
* Subqueries
* Data Exploration
* Business KPI Analysis

### Example Query

```sql
SELECT Vehicle_Type,
       AVG(Ride_Distance) AS Average_Distance
FROM bookings
GROUP BY Vehicle_Type;
```

---

## 📈 Dashboard KPIs

* Total Bookings
* Successful Rides
* Cancellation Rate
* Total Revenue
* Average Customer Rating
* Average Driver Rating
* Top Customers
* Revenue by Payment Method

---

## 📷 Dashboard Screenshots

### Overall Performance Dashboard

![Dashboard](ADD_IMAGE_LINK)

### Revenue Analysis

![Dashboard](ADD_IMAGE_LINK)

### Cancellation Analysis

![Dashboard](ADD_IMAGE_LINK)

### Customer & Driver Ratings

![Dashboard](ADD_IMAGE_LINK)

---

## 💡 Business Recommendations

* Reduce ride cancellations through improved driver allocation.
* Monitor low-rated drivers and provide targeted training.
* Increase customer retention through loyalty programs.
* Optimize vehicle availability during peak demand periods.
* Promote high-performing payment channels to improve transaction efficiency.

---

## 📁 Repository Contents

* OLA Project.pbix
* SQL Queries.sql
* Bookings.csv
* Dashboard Screenshots
* README.md

---

## 🎯 Project Outcome

This project demonstrates practical SQL querying, business analysis, KPI development, and Power BI dashboard creation skills required for Data Analyst roles. The analysis converts operational ride-booking data into meaningful insights that support better business decisions.




