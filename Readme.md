# 🚖 Ride Booking Analytics Dashboard (Power BI)

---

## 📌 Project Overview

This project focuses on analyzing ride booking data using **Power BI** to generate meaningful insights about **demand patterns, cancellations, and revenue performance**.
The dashboard provides an interactive and visual representation of ride-sharing operations to support data-driven decision-making.

---

## ❗ Problem Statement

Ride-sharing platforms generate large volumes of data, but without proper analysis, it is difficult to:

* Identify peak demand periods
* Understand cancellation behavior
* Track revenue performance
* Improve operational efficiency

This project addresses these challenges by transforming raw data into actionable insights.

---

## ⭐ Importance of the Project

* Helps in reducing ride cancellations
* Improves customer experience
* Identifies high-demand locations and peak hours
* Supports business decision-making
* Demonstrates real-world data analytics skills

---

## 📂 Dataset Details

* Source: Kaggle (Ride Booking Dataset)
* Size: 100,000+ records
* Data includes:

  * Booking ID
  * Date & Time
  * Pickup Location
  * Vehicle Type
  * Ride Distance
  * Booking Value
  * Status (Success, Cancelled, etc.)
  * Payment Method
  * Ratings

---

## 🔍 Sample Features

* `Booking_ID` – Unique ride identifier
* `Date` – Booking date
* `Time` – Booking time
* `Pickup_Location` – Ride origin
* `Vehicle_Type` – Type of vehicle
* `Ride_Distance` – Distance travelled
* `Booking_Value` – Fare amount
* `Status` – Ride status

---

## 🛠️ Tools & Technologies Used

* **Power BI** – Dashboard creation & visualization
* **Power Query** – Data cleaning & transformation
* **Excel** – Initial data handling

---

## ⚙️ Data Processing Workflow

1. **Data Collection**

   * Collected raw dataset from Kaggle

2. **Initial Data Handling (Excel)**

   * Opened dataset in Excel
   * Performed basic inspection
   * Checked for missing values and inconsistencies
   * Removed obvious unnecessary columns

3. **Data Import into Power BI**

   * Loaded dataset into Power BI

4. **Data Cleaning & Transformation (Power Query)**

   * Removed unwanted columns
   * Handled null values and errors
   * Corrected data types (Date, Time, Numeric)
   * Renamed columns for consistency

5. **Feature Engineering**

   * Created new columns:

     * Hour
     * Day of Week
     * Status categories

6. **DAX Measures Creation**

   * Total Rides
   * Total Revenue
   * Cancellation Rate
   * Average Fare
   * Revenue per Ride

7. **Dashboard Development**

   * Built multi-page dashboard
   * Added KPIs, charts, slicers
   * Applied formatting and layout

8. **Insight Generation**

   * Identified trends and patterns
   * Derived business insights

---

## 📊 Key Insights

* Majority of rides are successfully completed
* Peak demand occurs during specific hours
* Certain locations have higher cancellation rates
* Driver-side cancellations are significant
* Revenue increases with ride distance and varies by vehicle type

---

## 📸 Dashboard Preview

![Overview]
<img width="1157" height="650" alt="image" src="https://github.com/user-attachments/assets/3f684334-193f-4d36-86d7-099fd27870e2" />

![Cancellation]
<img width="1154" height="654" alt="image" src="https://github.com/user-attachments/assets/0100112d-090f-4489-8a96-5e4ec4d73d00" />

![Demand]
<img width="1154" height="647" alt="image" src="https://github.com/user-attachments/assets/5839973b-d45a-4b41-b67b-febebe45ae76" />

![Revenue]
<img width="1156" height="651" alt="image" src="https://github.com/user-attachments/assets/c04c980b-9fdf-420e-8a15-969013eb01f2" />





---

## 📁 Project Structure

```
ride-booking-analytics-dashboard/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── Ola_Booking_and_Cancellation_Analysis_Dashboard.pbix
│
├── Screenshots/
│   ├── Overview.png
│   ├── Cancellation_analysis.png
│   ├── Demand_analysis.png
│   └── Revenue&Performance.png
│── Icons/
│   ├── cabcel.png
│   ├── clock.png
│   ├── fare.png
│   ├── revenue.png
│   ├── taxi.png
│   └── location.png
└── README.md
```

---

## 🚀 Future Enhancement

* Add demand forecasting using predictive analytics
* Improve dashboard UI/UX
* Integrate real-time data
* Apply machine learning for cancellation prediction

---

## 👤 Author

**Karthikeyan P**


---

## 📌 Conclusion

This project demonstrates how raw ride booking data can be transformed into meaningful insights using Power BI.
It highlights the importance of data analytics in improving operational efficiency and decision-making in ride-sharing services.

---
