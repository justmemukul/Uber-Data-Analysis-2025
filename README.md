# 🚖 Uber Operational Performance Analysis (2025)

## 📌 Executive Summary
This project provides an advanced analytical review of Uber's operational performance using a dataset of **150,000 records**. By leveraging Power BI, I developed an interactive dashboard to evaluate booking efficiency, revenue drivers, and operational friction. 

The analysis identifies a critical **38% attrition rate** and provides strategic recommendations to improve customer retention and fleet optimization.

## 📊 Interactive Dashboard Highlights
* **Total Completed Bookings:** 92.55K
* **Total Revenue:** ~$31.7M+ (Primary drivers: Auto & Bike segments)
* **Customer Satisfaction:** 4.40/5.0 Avg. Rating
* **Key Tech Stack:** Power BI (DAX, Power Query), Advanced Excel, Data Modeling.

## 💡 Key Business Insights

### 1. The "Lost Booking" Challenge
The most significant finding is a **38% cancellation/drop-off rate** (57K lost bookings). 
* **Responsibility:** Customers account for **72%** of cancellations, while drivers account for **28%**.
* **Friction Points:** Top reasons include "Change of plans" and "Driver asked to cancel."

### 2. Revenue & Vehicle Dynamics
| Vehicle Segment | Completed Rides | Revenue Generated |
| :--- | :--- | :--- |
| **Auto** | 23,128 | $13M |
| **Bike** | 20,560 | $11M |
| **Premier Sedan** | 11,247 | $6.2M |
| **Uber XL** | 2,783 | $1.5M |

* **Payment Trends:** Digital payments dominate, with **UPI ($23.3M)** generating nearly double the revenue of Cash ($12.9M).

### 3. The Retention Gap
While the platform successfully acquired **83K New Customers**, only **15K** transitioned to "Regular" status. This suggests a strong marketing funnel but a need for better "sticky" features to build long-term loyalty.

### 4. Spatial & Temporal Peaks
* **Peak Hours:** 9:00 AM – 12:00 PM and 6:00 PM – 9:00 PM.
* **High-Density Hubs:** Khandsa (Top Pickup) and Adarsh Nagar (Top Drop).

## 🚀 Strategic Recommendations
1.  **Driver Incentives:** Address "Driver asked to cancel" incidents by offering bonuses for low cancellation rates during peak hours.
2.  **Loyalty Program:** Implement a tier-based system to convert the 83K new users into daily commuters.
3.  **Fleet Positioning:** Use predictive positioning for Autos and Bikes in Khandsa/Adarsh Nagar 30 minutes before peak windows.
4.  **Data Integrity:** Enforce mandatory cancellation reasons in-app to solve the "missing data" gap (102K blank entries).

## 📁 Project Structure
* `Uber_Analysis_Dashboard.pbix`: The core Power BI file.
* `Uber_Data_2025.xlsx`: Cleaned dataset.
* `Executive_Report.pdf`: Full detailed analysis report.
