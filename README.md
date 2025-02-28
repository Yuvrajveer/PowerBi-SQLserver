# 🚲 Yulu Bikes Dashboard - Power BI & SQL Server

## 📌 Project Overview
This project is a **Power BI dashboard** built using **SQL Server** as the backend to analyze and visualize data related to Yulu Bikes. The goal is to provide insights into bike usage, operational efficiency, and customer trends to help Yulu Bikes optimize its services.

## 🔧 Technologies Used
- **Power BI** - Data visualization and dashboard creation
- **SQL Server** - Data storage and management
- **SQL Queries** - Data extraction and transformation
- **DAX (Data Analysis Expressions)** - Advanced calculations in Power BI
- **ETL (Extract, Transform, Load) Pipeline** - Data processing and cleaning

## 📊 Features & Insights
- **User Demographics:** Breakdown of customers by age, gender, and location.
- **Ride Analytics:** Total trips, average ride duration, and peak usage hours.
- **Revenue Insights:** Earnings from rentals, subscription-based revenue.
- **Operational Efficiency:** Bike availability, maintenance status, and demand forecasting.
- **Geospatial Analysis:** Heatmap visualization of high-demand areas.

## 🏗️ Project Structure
```
📂 Yulu_Bikes_Dashboard
│── 📁 Data
│   ├── Raw_Data.sql  (Initial dataset)
│   ├── Processed_Data.sql  (Transformed dataset)
│── 📁 Reports
│   ├── Yulu_Bike_Dashboard.pbix  (Power BI dashboard file)
│── 📁 Documentation
│   ├── README.md  (This file)
│   ├── Data_Dictionary.xlsx  (Schema details)
│── 📁 Scripts
│   ├── ETL_Scripts.sql  (Data transformation scripts)
│── 📁 Images
│   ├── Dashboard_Screenshot.png  (Preview of the dashboard)
```

## 📂 Data Sources
The dataset used in this project consists of:
- **Customer Details** - User registrations, demographic info.
- **Trip Records** - Start time, end time, duration, and location.
- **Financial Transactions** - Payment details and revenue insights.
- **Bike Inventory** - Availability, maintenance logs, and station locations.


## 🚀 Setup & Installation
1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/Yulu_Bikes_Dashboard.git
   ```
2. **Restore the SQL Database** using `Raw_Data.sql`
3. **Run ETL scripts** (`ETL_Scripts.sql`) to process the data
4. **Open Power BI** and load `Yulu_Bike_Dashboard.pbix`
5. **Refresh Data Sources** to connect with SQL Server



