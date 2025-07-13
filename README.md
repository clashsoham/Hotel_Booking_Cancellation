# Hotel Booking Cancellation Analysis 🏨📉

This project analyzes hotel booking data to understand cancellation patterns and customer behavior. It provides insights that can help improve booking strategies and reduce cancellation rates.

## 📁 Dataset Overview

The dataset includes booking records for Resort and City hotels, with features such as:
- `is_canceled`: Indicates whether a booking was canceled (1) or not (0).
- `arrival_date_year` / `arrival_date_month`: Date of expected arrival.
- `adults`, `children`, `babies`: Number of guests.
- `country`: Country of origin of the booking.
- `reserved_room_type` vs `assigned_room_type`: For analyzing overbooking and upgrade patterns.
- `reservation_status` / `reservation_status_date`: Booking outcome and its finalization date.
- `room status`, `guest_type`: Custom indicators related to guest preferences and room satisfaction.

## 📊 Features

- Pivot Table summary for quick aggregation and trend spotting.
- Dashboard for interactive visualization of booking patterns.
- Exploratory Data Analysis (EDA) to:
  - Identify cancellation trends.
  - Compare guest demographics.
  - Detect mismatches between reserved and assigned rooms.

## 🔍 Key Insights

- Most bookings are made by couples.
- Room mismatch and guest origin may influence cancellation rates.
- Seasonal patterns (months and years) affect cancellation trends.

## 🛠️ Tools Used

- Microsoft Excel (Pivot & Dashboard)
