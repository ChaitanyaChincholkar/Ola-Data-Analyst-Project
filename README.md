# 🚗 OLA Data Analyst Dashboard (Power BI Project)

This project presents an interactive OLA Ride Analysis Dashboard built using Power BI, PostgreSQL, and Excel.

The dashboard provides insights into:
- Booking trends
- Revenue analysis
- Cancellation reasons
- Vehicle performance
- Customer & Driver ratings

### 🔹 Overall Performance Overview
- Total Bookings
- Total Revenue
- Booking Status Breakdown
- Daily Booking Trend
<img width="2849" height="1345" alt="Screenshot 2026-02-16 152710" src="https://github.com/user-attachments/assets/f6b99e8f-7991-4879-8aab-ceeec915edf1" />

### 🚘 Vehicle Type Analysis
- Booking Value by Vehicle
- Average Distance Travelled
- Total Distance Covered
<img width="2332" height="1340" alt="Screenshot 2026-02-16 152728" src="https://github.com/user-attachments/assets/f96c6e84-e873-4a61-82bd-84ce16ac2a2f" />

### 💰 Revenue Analysis
- Revenue by Payment Method
- Daily Revenue Trend
- Top Customers
<img width="2312" height="1356" alt="Screenshot 2026-02-16 152742" src="https://github.com/user-attachments/assets/e746e465-3656-4102-be0d-ae62c4098d8e" />

### ⭐ Ratings Analysis
- Driver Ratings by Vehicle Type
- Customer Ratings by Vehicle Type
<img width="2282" height="1332" alt="Screenshot 2026-02-16 152817" src="https://github.com/user-attachments/assets/a139e7f2-3926-49c9-b70b-bebc4e2668de" />

Built an end-to-end OLA Ride Analytics Dashboard using Power BI to analyze bookings, revenue trends, cancellations, and ratings for business insights.

## 🛠 Tools Used
- Power BI
- SQLWorkbench
- Excel
  
   
   ---------->OLA Data Analyst Project<----------------
Make sure orders cancelled by customers should not be more than 7%
Make sure orders cancelled drivers should not be more than 18%
Also, increase the number of orders on weekends and match days. Keep match day by using the
following dates.
keep incomplete rides less than 6%
Keep order value high on weekends
in Food Category keep around 67 Indian
keep order ID with 10 digits starting with CNR and then digits
keep orders under 500 value 70%
keep orders above 500 value 28%
keep remaining orders above 1000

************** SQL Questions**************:
1. Retrieve all successful bookings:
2. Find the average ride distance for each vehicle type:
3. Get the total number of cancelled rides by customers:
4. List the top 5 customers who booked the highest number of rides:
5. Get the number of rides cancelled by drivers due to personal and car-related issues:
6. Find the maximum and minimum driver ratings for Prime Sedan bookings:
7. Retrieve all rides where payment was made using UPI:
8. Find the average customer rating per vehicle type:
9. Calculate the total booking value of rides completed successfully:
10. List all incomplete rides along with the reason:

************************Power BI Questions***********************:
1. Ride Volume Over Time
2. Booking Status Breakdown
3. Top 5 Vehicle Types by Ride Distance
4. Average Customer Ratings by Vehicle Type
5. cancelled Rides Reasons
6. Revenue by Payment Method
7. Top 5 Customers by Total Booking Value
8. Ride Distance Distribution Per Day
9. Driver Ratings Distribution
10. Customer vs. Driver Ratings
Data Columns
1. Date
2. Time
3. Booking_ID
4. Booking_Status
5. Customer_ID
6. Vehicle_Type
7. Pickup_Location
8. Drop_Location
9. V_TAT
10. C_TAT
11. cancelled_Rides_by_Customer
12. cancelled_Rides_by_Driver
13. Incomplete_Rides
14. Incomplete_Rides_Reason
15. Booking_Value
16. Payment_Method
17. Ride_Distance
18. Driver_Ratings
19. Customer_Rating
    
