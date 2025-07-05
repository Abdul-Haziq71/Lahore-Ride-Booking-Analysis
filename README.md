# 🚖 Lahore Ride Booking Analysis (SQL + Power BI)

This project analyzes a month’s worth of ride booking data (25,000 rows) for Lahore city.  
It was done using **SQL** for data analysis and **Power BI** for interactive dashboards.  
The goal is to uncover trends, customer behavior, cancellation patterns, and performance by vehicle type.

---

## 📁 Project Structure


---

## 📌 Tools Used

- **Power BI Desktop** – For visualization and interactive dashboards
- **SQL Server** – For querying large datasets
- **Excel** – For saving query results and small data prep

---

## 🗃️ Dataset Details

- **Rows:** 25,000
- **City:** Lahore  
- **Period:** 1 month  
- **Columns Included:**
  - Booking ID, Date, Time
  - Vehicle Type (Bike, Auto, Prime Sedan, etc.)
  - Booking Status (Success, Cancelled, Incomplete)
  - Ratings (Customer + Driver)
  - Booking Value, Ride Distance
  - Cancellation Reasons (By Customer & Driver)

---

## 🧮 SQL Analysis

Some questions answered using SQL:
1. Retrieve all successful bookings  
2. Find the average ride distance for each vehicle type  
3. Count of cancelled rides by customers  
4. Top 5 customers with highest number of bookings  
5. Driver cancellations due to personal issues  
6. Max & Min driver ratings for Prime Sedan  
7. Total booking value for successful rides  
8. All incomplete rides with reasons

👉 SQL results saved in `sql_results/SQL_Analysis_Results.xlsx`

---

## 📊 Power BI Dashboard

The Power BI dashboard is organized into **5 pages**, each covering related insights:

### 🔹 Page 1: Booking Volume & Status (Q1, Q2)
- Daily ride trends
- Booking success vs. cancellation breakdown

### 🔹 Page 2: Vehicle Distance Analysis (Q3)
- Top 5 vehicle types by total ride distance

### 🔹 Page 3: Ratings & Cancellations (Q4, Q5, Q6)
- Avg customer ratings per vehicle
- Cancellation reasons (by customer & driver)
- Revenue by payment method *(if included)*

### 🔹 Page 4: Customer Value & Distance Trends (Q7, Q8)
- Top 5 customers by booking value
- Daily ride distance trends

### 🔹 Page 5: Rating Distributions (Q9, Q10)
- Driver rating distribution
- Comparison: Customer vs Driver rating

✅ The dashboard is fully interactive with slicers for:
- Date
- Booking Status
- Vehicle Type
- Pickup Location

---

## 📈 Key Insights

- ~62% of bookings were successful as per target
- Most popular vehicle type: **Bike**
- Top cancellation reason (Customer): *Driver not moving toward pickup*
- Prime Sedan has highest average driver ratings
- Bookings peaked during weekends and evenings
- Customer vs Driver ratings are closely aligned

---

## 📂 How to Use the Files

1. Clone or download the repository
2. Open the `.pbix` file using Power BI Desktop
3. Use slicers and filters to explore data
4. SQL queries are documented and saved as Excel results

---

## 🔗 Connect with Me

📧 Email: abdulhazik71@gmail.com
🌐 Linkedin: https://www.linkedin.com/in/abdulhaziq71
🐙 GitHub: https://github.com/Abdul-Haziq71

---

