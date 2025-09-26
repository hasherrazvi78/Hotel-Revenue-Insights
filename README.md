# 🏨 Hotel Revenue Insights Dashboard

### A deep dive into hotel booking data for smarter business decisions.

## Project Overview
This project is all about transforming raw hotel booking data into actionable business intelligence. I built a dynamic dashboard in **Power BI** to provide key insights that can help a hotel optimize revenue, track occupancy rates, and understand booking trends.

---

## 🛠️ Data & Technology
* **Data Source**: The analysis is powered by a dataset of hotel bookings. The data is structured using a **star schema** for an efficient and robust model. It includes dimension tables for hotels, rooms, and dates, along with fact tables for individual and aggregated bookings.
* **Business Intelligence**: The entire analysis and final visualizations were created using **Power BI**.
* **Analysis Language**: **DAX** (Data Analysis Expressions) is used to create calculated columns and advanced measures.

---

## 📂 Key Project Components
* **Data Files (`.csv`)**: These are the structured datasets used for the final analysis.
    * `dim_date.csv`
    * `dim_hotels.csv`
    * `dim_rooms.csv`
    * `fact_bookings.csv`
    * `fact_aggregated_bookings.csv`
* **Documentation**:
    * `metrics list.xlsx` (in CSV format): A list of all the DAX measures and calculated columns used in the report.
* **Final Report**:
    * `Hotel Revenue Insights.pdf`: A static version of the final dashboard for quick viewing.
* **Power BI Files**:
    * `hotel_revenue_insights.pbix`: The primary Power BI report file with the complete data model and visualizations.
    * `hotel_revenue_insights.pbit`: A reusable template file that allows others to connect to their own dataset.

---

## 🚀 How to View the Dashboard
1.  Download the `hotel_revenue_insights.pbix` file from this repository.
2.  Install **Power BI Desktop** on your computer.
3.  Open the `.pbix` file to explore the interactive dashboard and gain insights into the hotel's performance.
