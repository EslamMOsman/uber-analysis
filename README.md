#  Uber Rides Data Analysis  

## Project Overview  
This project is my **first full data analysis project**. Since it is an initial attempt, the work may contain mistakes or incomplete use of the data. I am still learning and practicing to improve my analytical skills, so any feedback is highly appreciated.  

The dataset comes from an **Uber-like ride-hailing application**, and includes details such as:  
- Ride dates and times  
- Vehicle types  
- Trip durations  
- Customer and driver ratings  
- Ride status (completed, cancelled, or incomplete)  
- Reasons for cancellations  
- Payment methods  

The goal of this project is to **analyze patterns in rides, cancellations, and customer/driver behavior**, while practicing data analysis and visualization skills.  

---

## 📊 Key Findings  

### 1. Order Cancellations  
- Most cancellations were made by **drivers**, followed by **customers**.  
- **August** recorded the highest number of cancellations by drivers (especially due to lack of available cars).  
- **July** had the highest number of cancellations by customers.  

![Booking Status by Month](booking_status_by_month.png)  
![Cancelled by Customer Trend](Trend_of_Cancelled_by_Customer_per_Month.png)  
![Cancelled by Driver Trend](Trend_of_Cancelled_by_Driver_per_Month.png)  

---

### 2. Ride Demand by Day & Time  
- In **August**, the highest bookings were on **Saturday and Thursday**.  
- Cancellations (by both drivers and customers) occurred most in the **morning and afternoon**, followed by the evening.  

![Booking Count by Day in August](booking_count_by_day_in_August.png)  
![Cancelled by Customer by Time Period](Cancelled_by_Customer_booking_status_by_time_period_august_daily.png)  
![Cancelled by Driver by Time Period](Cancelled_by_Driver_booking_status_by_time_period_august_daily.png)  

---

### 3. Cancellation Reasons  

#### By Customers  
- Wrong Address → 2362  
- Change of Plans → 2353  
- Driver not moving to pickup → 2335  
- Driver asked to cancel → 2295  
- AC not working → 1155  

![Reasons Cancelled by Customer](reasons_cancelled_by_customer.png)  

#### By Drivers  
- Customer-related issues → 6837  
- Customer was sick → 6751  
- Personal & car-related issues → 6726  
- More than permitted people → 6686  

![Reasons Cancelled by Driver](reasons_cancelled_by_driver.png)  

---

### 4. Incomplete Rides  
Most common reasons:  
- Customer Demand → 3040  
- Vehicle Breakdown → 3012  
- Other Issues → 2948  

![Incomplete Rides Reasons](incomplete_rides_reasons.png)  

---

### 5. Payment Methods  
The most widely used payment methods were:  
- **UPI**  
- **Cash**  

![Payment Methods](payment_methods.png)  

---

### 6. Vehicle Types  
The top 3 vehicle types used were:  
- Go Mini  
- Go Sedan  
- Bike  

![Number of Completed Orders by Vehicle Type](Number_of_Completed_Orders_by_Vehicle_Type.png)  

Most rides were completed in the **Afternoon** for almost all vehicle types.  

![Completed Rides by Vehicle Type and Time Period](Completed_Rides_by_Vehicle_Type_and_Time_Period.png)  

---

## 📝 Conclusion  
This project gave me hands-on experience in **data cleaning, exploration, and visualization**. While it is only my first project, I was able to uncover meaningful insights about **ride demand, cancellations, payment behavior, and vehicle usage**.  

I look forward to improving my skills further and applying more advanced analysis techniques in the future.  

