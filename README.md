# ✈️ Airline Performance & Flight Delay Analysis | Power BI

<p align="center">
  <img src="https://img.shields.io/badge/POWER%20BI-Analytics-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-Measures-4472C4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Power%20Query-ETL-217346?style=for-the-badge&logo=powerbi&logoColor=white" />
  <img src="https://img.shields.io/badge/Records-3M-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

<p align="center">
  <b>Turning Flight Data into Meaningful Insights Through Interactive Power BI Dashboards.</b>
</p>

---

## 📌 About The Project

The **Airline Performance & Flight Delay Analysis Dashboard** is an interactive Business Intelligence project developed using Microsoft Power BI.

This project analyzes approximately 3 million flight records covering the period 2019–2023 to explore airline performance, flight delays, cancellations, airport activities, and operational trends.

The dashboard transforms raw flight data into meaningful insights using interactive visualizations, dynamic KPIs, geographical analysis, and advanced Power BI functionalities.

The report is designed to help users understand airline performance, identify delay patterns, analyze cancellation causes, and explore historical flight trends.

## 📊 Dashboard Highlights

| KPI | Dashboard Result |
|---|---:|
| ✈️ Total Flights | 3M |
| ❌ Total Cancelled | 79K |
| ⏱️ On-Time Rate | 82.3% |
| 📉 Cancellation Rate | 2.64% |
| 🛫 Average Departure Delay | 10.1 Minutes |
| 🛬 Average Arrival Delay | 4.3 Minutes |

*Values represent the results displayed in the dashboard's current overall view.*

## 🎯 Project Objectives

- Analyze overall airline operational performance.
- Compare flight performance across airlines.
- Identify departure and arrival delay patterns.
- Understand flight cancellation causes.
- Explore airport locations and geographical patterns.
- Analyze historical flight volume and delay trends.
- Build interactive dashboards with dynamic filtering.
- Implement advanced Power BI reporting features.

## 📂 Dataset

**Dataset Name:** Flight Delay and Cancellation Dataset (2019–2023)

**Dataset Author:** Patrick Zelazko

**Source:** Kaggle

🔗 [Download Dataset from Kaggle](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023)

**Dataset Information:**
- Approximately 3 million sample flight records used in this project.
- 32 data attributes.
- Covers flight operations from 2019 to 2023.
- Includes airline, airport, route, delay, and cancellation information.

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Measures and calculations |
| Data Modeling | Data relationships and analysis |
| Bookmarks | Interactive filter visibility |
| Field Parameters | Dynamic metric selection |
| Numeric Range Parameters | Delay threshold analysis |

---

## 📸 Dashboard Preview

### 1️⃣ Overview Dashboard

<img width="1162" height="648" alt="image" src="https://github.com/user-attachments/assets/178c290b-3eed-4de1-9854-3b6437cd00d6" />


The Overview page provides a complete summary of flight operations through KPI cards, cancellation analysis, flight outcome distribution, and airline comparison.

**Key Features:**
- Total Flights and Total Cancelled KPI cards.
- On-Time Rate and Cancellation Rate.
- Flight Cancellation by Cause.
- On-Time Performance Gauge against an 80% target.
- Flight Outcome Distribution.
- Interactive Airline and Year slicers.
- Dynamic Metric Selector.

### 2️⃣ Airline Performance Dashboard

<img width="1162" height="656" alt="image" src="https://github.com/user-attachments/assets/09a62203-f4fd-4799-8a67-ded18c476826" />


This page focuses on comparing airline performance and identifying airlines with higher cancellation counts and departure delays.

**Key Features:**
- Top 10 Airlines by Cancellation Count.
- Top 10 Airlines by Average Departure Delay.
- Airline Cancellation Rate Heatmap by Year.
- Airline Performance KPI Table.
- Year-based filtering.

### 3️⃣ Route & Airport Map

<img width="1162" height="648" alt="image" src="https://github.com/user-attachments/assets/cb5df266-d40e-432b-bfca-0889ab8a7413" />


This page provides geographical insights into flight operations and airport-level performance.

**Key Features:**
- US Departure Airports – Flight Volume and Average Delay.
- US State Cancellation Rate Map.
- Interactive airport bubbles.
- Geographical analysis.
- Flight Year and Minimum Delay slicers.

### 4️⃣ Drill-Through Detail

<img width="1106" height="622" alt="image" src="https://github.com/user-attachments/assets/c778509e-a59f-421c-b8aa-7bc2f6f6b404" />

This page provides airline-specific information through Power BI Drill-Through functionality.

**Key Features:**
- Airline-specific Total Flights KPI.
- Cancellation Rate KPI.
- Monthly Cancellation Analysis.
- Yearly On-Time Performance.
- Detailed Flight Information Table.
- Back Navigation Button.

### 5️⃣ Trends & Forecast

<img width="1157" height="647" alt="image" src="https://github.com/user-attachments/assets/9128226b-18da-4dbb-9b39-6f95fbd44817" />


This page analyzes historical flight performance and explores future flight volume trends.

**Key Features:**
- Monthly Flight Volume by Year (2019–2023).
- Monthly Average Departure Delay by Year.
- Flights Above Minimum Delay KPI.
- Interactive Minimum Delay Parameter.
- Monthly Flight Volume Trend.
- Six-Month Forecast Visualization.

### 6️⃣ Mobile Dashboard Layout

A dedicated mobile-friendly layout designed to make important dashboard information accessible on smaller screens.

**Key Features:**
- Total Flights KPI.
- Cancellation Rate KPI.
- Destination-wise Flight Volume.
- Compact mobile visualization layout.

---

## ⚡ Advanced Power BI Implementations

This project includes practical implementation of advanced Power BI features across Tasks 1–10.

| # | Feature | Implementation |
|---|---|---|
| 01 | 🔖 Bookmarks | Show/Hide Slicer Panel |
| 02 | 🧭 Navigation | Custom Page Navigation Bar |
| 03 | 🔍 Drill-Through | Airline-level detail page |
| 04 | 🎚️ Numeric Range Parameter | Minimum Delay Selection |
| 05 | 🔄 Field Parameters | Dynamic Metric Selection |
| 06 | 🖱️ Custom Tooltips | Airport Information Tooltip |
| 07 | 🎛️ Edit Interactions | Visual Interaction Control |
| 08 | 📱 Mobile Layout | Mobile-Optimized Report |
| 09 | 📈 Trend Analysis | Historical Performance Trends |
| 10 | 🔮 Forecasting | Six-Month Flight Volume Forecast |

## 🧮 DAX Measures

DAX was used to create analytical measures and dynamic calculations.

**Key Measures:**

- Total_Flights
- Total_Cancelled
- Avg_Dep_Delay
- Avg_Arr_Delay
- On_Time_Rate%
- Cancellation_Rate%
- Flights_Above_Min_Delay

**Example – Flights Above Minimum Delay**

```dax
Flights_Above_Min_Delay =
CALCULATE(
    [Total_Flights],
    FILTER(
        FlightData,
        FlightData[ARR_DELAY] >=
        SELECTEDVALUE(
            'Min_Delay_Minutes'[Min_Delay_Minutes Value]
        )
    )
)
```

This measure calculates flights based on the minimum arrival delay selected by the user.

**Dynamic Metric Selection**

Implemented Field Parameters to switch between five analytical measures:

1. Total Flights
2. Total Cancelled
3. Average Departure Delay
4. Average Arrival Delay
5. On-Time Rate %

## 🎨 Dashboard Design & Formatting

- Consistent red and white dashboard theme.
- Professional navigation buttons.
- Organized KPI cards.
- Interactive slicers and visual filters.
- Conditional formatting in analytical tables.
- Descriptive chart titles.
- Consistent visual alignment.
- Mobile-friendly report design.

## 📥 Download Project Files

| Resource | Access |
|---|---|
| 📊 Power BI PBIX File |  https://drive.google.com/file/d/1TePx_3NpdI2cPC0cYdt-g9qSDyW9GXFP/view
| 📂 Dataset | [Kaggle Dataset](https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023) |
| 🎥 Video Demonstration | [Watch Project Video](YOUR_GOOGLE_DRIVE_VIDEO_LINK) |

## 🎥 Video Demonstration

Watch the complete project walkthrough to explore the dashboard design, analytical insights, and interactive features.

**▶️ [Watch Full Project Demonstration](YOUR_GOOGLE_DRIVE_VIDEO_LINK)**

The demonstration covers:
- Overview and KPI analysis.
- Airline performance comparison.
- Airport and geographical analysis.
- Drill-Through functionality.
- Trends and Forecast.
- Bookmark-based navigation.
- Dynamic Field Parameters.
- Numeric Range Parameters.
- Custom Tooltips.
- Mobile Dashboard Layout.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Working with large datasets in Power BI.
- Data cleaning and transformation using Power Query.
- Creating DAX measures and KPIs.
- Building interactive dashboards.
- Implementing bookmarks and navigation.
- Using Field Parameters and Numeric Range Parameters.
- Creating Drill-Through reports.
- Designing custom report tooltips.
- Managing visual interactions.
- Creating trend analysis and forecast visualizations.
- Developing mobile-friendly dashboards.

## 👩‍💻 About Me

**Simran Gohel**

Aspiring Data Analyst | Power BI | SQL | Python | Excel

🔗 **GitHub:** [simrangohel70-lab](https://github.com/simrangohel70-lab)


---

<p align="center">
  <b>✈️ Turning Data into Insights, One Flight at a Time!</b>
  <br/><br/>
  ⭐ Thank you for visiting my project!
</p>
