# 🚖 Uber Trip Analysis – Power BI Dashboard

A comprehensive Power BI solution designed to analyse Uber trip data and uncover insights related to bookings, revenue, trip efficiency, time-based demand, and location behaviour.  
This project consists of **three interactive dashboards** built using advanced DAX measures, dynamic visuals, bookmarks, drill-throughs, and performance-enhancing features.

---

## 📌 Project Overview

This project helps stakeholders understand:

- Booking patterns across cities and time ranges
- Revenue and booking value distribution
- Trip efficiency in terms of distance and duration
- Time-based demand behaviour (hourly, daily, weekly)
- Location-wise pickup and drop-off hotspots
- Vehicle performance insights based on customer preference

The primary goal is to support **data-driven decision-making** for pricing, resource allocation, and operational optimization.

---

## 📊 Dashboard 1: Overview Analysis

This dashboard provides top-level KPIs and overall performance insights.

### **Key KPIs**
- **Total Bookings**
- **Total Booking Value**
- **Average Booking Value**
- **Total Trip Distance**
- **Average Trip Distance**
- **Average Trip Time**

### **Main Visuals & Insights**
- Dynamic **Measure Selector** (Bookings, Revenue, Distance)
- **Dynamic Chart Titles** (auto updates based on selection)
- Breakdown by **Payment Type** (Cash, Card, Wallet, etc.)
- Breakdown by **Trip Type** (Day vs Night)
- Vehicle Type matrix with conditional formatting
- **Top 5 Pickup & Drop-off Locations**
- **Most Frequent Pickup Point**
- **Most Frequent Drop-off Point**  
- **Farthest Trip Analysis**
- Slicers for Date, City, Vehicle Type, Payment Type, Trip Type

---

## ⏱ Dashboard 2: Time Analysis

Focused on understanding trip volume trends across time intervals.

### **Visuals Included**
- **Area Chart by Pickup Time (10-minute intervals)**
- **Line Chart by Day Name (Mon–Sun)**
- **Heatmap (Hour × Day)** showing peak and off-peak hours
- Global Dynamic Measure Selector applied across all visuals

This dashboard supports decisions related to **driver availability**, **surge pricing**, and **trip scheduling**.

---

## 📄 Dashboard 3: Details / Grid Tab

A detailed, drill-through based dashboard for record-level analysis.

### **Features**
- Detailed grid/table listing all trip attributes
- Drill-through from Overview or Time dashboards
- Bookmark: **“View Full Data”** to toggle between filtered and full dataset
- Ideal for audits, validations, and deep data exploration

---

## ✨ Additional Enhancements

- **Data Details Bookmark** explaining KPIs, tables, and data refresh
- **Clear All Filters Button** for quick reset
- **Download Raw Data Button** (via Power Automate)
- Custom tooltips showing Avg Distance, Avg Fare & Trip Time
- Conditional formatting and enhanced user-friendly UI design

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Dashboarding | Power BI |
| Data Cleaning | Power Query |
| Data Modeling | Star Schema |
| Calculations | DAX |
| Automation | Power Automate (optional for export) |

---
