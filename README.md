# ✈️ Airline Delay Analysis Dashboard | Power BI

An interactive **Airline Operations & Delay Analysis Dashboard** built using **Microsoft Power BI** to analyze flight activity, airline performance, airport operations, delays, cancellations, diversions, and operational trends.

The project transforms raw airline flight data into a **four-page Business Intelligence dashboard** using **Power Query, Data Modeling, DAX, interactive visualizations, slicers, and drill-through analysis**.

---

## 📊 Dashboard Preview

### 1. Executive Summary

Provides a high-level overview of airline operations, flight volume, delays, cancellations, diversions, and operational performance.

![Executive Summary](Power%20Bi/Page1_Executive_Summary.png)

---

### 2. Geographic Analysis

Analyzes flight activity and delay patterns across origin and destination airports.

![Geographic Analysis](Power%20Bi/Page2_Geographic_Analysis.png)

---

### 3. Airline Performance

Compares airline performance based on flight volume, delays, cancellations, and operational reliability.

![Airline Performance](Power%20Bi/Page3_Airline_Performance.png)

---

### 4. Flight Operations & Delay Analysis

Analyzes delay patterns across months, days of the week, flight operations, and delay causes.

![Flight Operations](Power%20Bi/Page4_Flight_Operations.png)

---

# 🎯 Business Problem

Airline delays and cancellations can negatively affect passenger experience, airline efficiency, airport operations, and overall service reliability.

The objective of this project is to analyze historical flight data and identify **where, when, and why delays occur**, while comparing operational performance across airlines and airports.

The dashboard answers questions such as:

- Which airlines experience higher levels of delays?
- Which airports have the highest flight activity?
- Which airports experience greater delay concentrations?
- What are the primary causes of flight delays?
- How do delays vary across months and days of the week?
- How frequently are flights cancelled or diverted?
- Which airlines have higher cancellation rates?
- How does flight volume relate to operational performance?

---

# 🎯 Project Objectives

The main objectives of the project were to:

1. Clean and transform raw airline flight data using **Power Query**.
2. Build a structured data model for analytical reporting.
3. Develop reusable **DAX measures** for operational KPIs.
4. Analyze airline and airport performance.
5. Identify the major contributors to flight delays.
6. Analyze temporal patterns in flight operations.
7. Build an interactive four-page Power BI dashboard.
8. Convert operational data into actionable business insights.

---

# 📊 Dashboard Pages

## 1️⃣ Executive Summary

Provides a consolidated overview of overall airline operations.

### Key Metrics

- Total Flights
- Total Airlines
- Cancelled Flights
- Diverted Flights
- Average Departure Delay
- Average Arrival Delay

### Visual Analysis

- Monthly Flight Volume
- Delay Cause Analysis
- Flight Status Overview
- Top Airline Analysis
- Operational KPI Cards

![Executive Summary](Power%20Bi/Page1_Executive_Summary.png)

---

## 2️⃣ Geographic Analysis

Analyzes flight activity and delay patterns across airports.

### Analysis Includes

- Origin Airport Activity
- Destination Airport Activity
- Geographic Flight Distribution
- Airport-Level Delay Comparison
- Top Origin Airports
- Top Destination Airports
- Flight Concentration by Airport

The geographic analysis helps identify airports with significant traffic volumes and areas where delays may be concentrated.

![Geographic Analysis](Power%20Bi/Page2_Geographic_Analysis.png)

---

## 3️⃣ Airline Performance

Compares airline operational performance using multiple KPIs.

### Analysis Includes

- Airline Flight Volume
- Average Departure Delay
- Average Arrival Delay
- Cancellation Rate
- Airline Delay Minutes
- Delay Cause Distribution
- Flight Status
- Airline Ranking

This page allows users to compare airlines using both **volume-based and performance-based metrics**.

![Airline Performance](Power%20Bi/Page3_Airline_Performance.png)

---

## 4️⃣ Flight Operations & Delay Analysis

Analyzes operational and delay patterns over time.

### Analysis Includes

- Delay Cause Analysis
- Monthly Delay Trends
- Day-of-Week Analysis
- Delay Severity
- Delay Distribution
- Flight Operations Trends
- Interactive Filtering

This page helps identify recurring temporal patterns and understand when delays are more likely to occur.

![Flight Operations](Power%20Bi/Page4_Flight_Operations.png)

---

# 📈 Key Performance Indicators

| KPI | Description |
|---|---|
| **Total Flights** | Total number of flights analyzed |
| **Total Airlines** | Number of airlines represented |
| **Cancelled Flights** | Total number of cancelled flights |
| **Diverted Flights** | Total number of diverted flights |
| **Average Departure Delay** | Average departure delay in minutes |
| **Average Arrival Delay** | Average arrival delay in minutes |
| **Average Air Time** | Average time spent in flight |
| **Average Distance** | Average flight distance |
| **Total Delay Minutes** | Total accumulated delay duration |
| **Weather Delay Minutes** | Delays attributed to weather |
| **Airline Delay Minutes** | Delays attributed to airline operations |
| **Air System Delay Minutes** | Delays caused by the air traffic system |
| **Security Delay Minutes** | Delays caused by security-related issues |
| **Late Aircraft Delay Minutes** | Delays caused by late-arriving aircraft |
| **Cancellation Rate** | Percentage of flights that were cancelled |

---

# 🔍 Key Analytical Areas

## ✈️ Airline Performance

Airlines are compared using:

- Flight volume
- Average departure delay
- Average arrival delay
- Cancellation rate
- Total delay minutes
- Delay causes

This allows identification of airlines with relatively stronger or weaker operational performance.

---

## 🛫 Airport Analysis

Airport-level analysis focuses on:

- Flight activity
- Origin airports
- Destination airports
- Delay concentrations
- Geographic distribution

This helps identify high-volume airports and locations that may require operational attention.

---

## ⏱️ Delay Cause Analysis

Flight delays are categorized into major operational causes:

- **Airline Delay**
- **Weather Delay**
- **Air System Delay**
- **Security Delay**
- **Late Aircraft Delay**

The analysis helps determine which factors contribute most to total delay time.

---

## 📅 Time-Based Analysis

The dashboard analyzes operational patterns across:

- Months
- Days of the week
- Flight periods
- Delay severity

This makes it possible to identify recurring temporal patterns in airline delays.

---

## 🛑 Flight Status Analysis

Flight outcomes are analyzed across:

- On-Time Flights
- Delayed Flights
- Cancelled Flights
- Diverted Flights

---

# 💡 Key Insights

The dashboard enables users to identify:

- Airlines with relatively higher delay activity.
- Airlines with higher cancellation rates.
- Airports with significant flight volumes.
- Airports with concentrated delay activity.
- Major contributors to total delay minutes.
- Seasonal patterns in flight delays.
- Day-of-week variations in operational performance.
- Differences in performance between airlines.
- The relationship between flight volume, delays, cancellations, and diversions.

> **Note:** The specific findings depend on the filters and selections applied within the dashboard.

---

# 🔄 Data Analytics Workflow

```text
Raw Airline Flight Data
          │
          ▼
    Data Cleaning
          │
          ▼
   Power Query ETL
          │
          ▼
    Data Modeling
          │
          ▼
   DAX Calculations
          │
          ▼
   KPI Development
          │
          ▼
 Data Visualization
          │
          ▼
 Interactive Dashboard
          │
          ▼
 Business Insights
