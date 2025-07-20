# 🚀 Enquiry Management System (EMS) Dashboard – Power BI

Welcome to the **EMS Dashboard** repository! This project is built using **Power BI** to monitor and analyze customer enquiries, test rides, follow-ups, and retail performance at a dealer and business level.

## 📂 Project Overview

The EMS dashboard helps visualize and interpret large-scale enquiry and retail data to identify performance trends, conversion efficiencies, and regional gaps.

- 🎯 **Objective**: To track, monitor, and improve customer enquiry conversion efficiency across all dealer points.
- 📅 **Data Period**: April to March (FY 2023-25)
- 📊 **Tool Used**: Power BI Desktop

---

## 📃 Dashboard Pages Description

### 🔹 **Page 1: EMS – Business Performance Overview**

Provides a macro-level performance summary of enquiries and retails by month.

- **Filters**: Financial Year, Month, Zone, State, Town, Dealer Code
- **KPIs**:
  - LY/TY Enquiry & Retail
  - Enquiry & Retail GOLY%
  - Conversion Ratios (LY vs TY)
  - Gain/Loss (%) vs Last Year
- **Visuals**:
  - YOY Comparison (Donut Chart)
  - Spartan vs Non-Project Dealer Trends (Line Chart)
  - Gain/Loss by Dealer Type (Bar Chart)

✅ **Key Formulas**:
- `Enquiry GOLY% = (TY Enquiry - LY Enquiry) / LY Enquiry * 100`
- `Retail GOLY% = (TY Retail - LY Retail) / LY Retail * 100`
- `Gain/Loss = TY Conversion% - LY Conversion%`

---

### 🔹 **Page 2: EMS – Dealer-Wise Customer Journey**

Breaks down customer journey insights at dealer level.

- **Filters**: FY, Month, Zone, State, Dealer, Town
- **Metrics**:
  - Total Enquiry, Test Ride Offered/Taken
  - Follow-Up Effectiveness (Same Day, >=3, >=5)
  - Enquiry Status (Open, Progress, Postponed)
  - Final Status (Converted, Lost, Booked, Retailed)

📌 **Highlights**:
- Quick snapshot of total enquiry conversion process
- Follow-up patterns help identify dealer gaps
- Retail data aggregated and mapped with enquiry flow

---

### 🔹 **Page 3: Dashboard Summary**

A professionally written visual summary page explaining:

- Page-wise objective
- KPI calculation logic
- Key insights from visuals
- User guide for filters and interpretations

---

## 🧮 Dataset Structure

Primary data table: `EMS`

| Column Name | Description |
|-------------|-------------|
| Zone, State, Town, Dealer_Code | Dealer Geography |
| Project, Month, Year, Date     | Time Period |
| Walkins_Enquiry, Test_Ride_Offered, Test_Ride_Taken | Initial Interaction |
| Followed_Up, Same_Day_Followed_Up, Followed_Up_>=3, >=5 | Follow-Up Details |
| Open_Enquiry, Enquiry_in_Progress, Enquiry_Postponed | Mid-Funnel Tracking |
| New_Enquiry, Enquiry_Closed_Lost, Enquiry_Converted | Final Funnel Status |
| Booked, Retailed, Same_Day_Retailed, Retails_for_the_Month | Booking & Retail Metrics |

---

## 📸 Screenshots

| Page | Description |
|------|-------------|
| ![Page 1] <img width="1291" height="809" alt="Screenshot 2025-07-20 193418" src="https://github.com/user-attachments/assets/1b40ce33-65b5-4ea7-8aaf-a38433740411" />
 | Business Performance |
| ![Page 2] <img width="1293" height="811" alt="Screenshot 2025-07-20 193504" src="https://github.com/user-attachments/assets/163c38a1-52ff-439e-9840-10c75260f42c" />
 | Dealer Journey |
| ![Page 3] <img width="1294" height="811" alt="Screenshot 2025-07-20 193525" src="https://github.com/user-attachments/assets/0406dd85-18a3-4233-a4d8-078e7679d79c" />
 | Summary Explanation |

---

## 🛠️ How to Use

1. Clone or download the repository
2. Open `.pbix` file in Power BI Desktop (file not included here)
3. Use the filters at top to select desired time frame, zone, or dealer
4. Use the summary page for navigation and explanation

---

## 👨‍💼 Created By

- **Name**: Aman Kumar  Shrivastav

