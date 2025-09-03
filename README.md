# 🏨 Hotel Booking Data Cleaning & Preparation Project

## 📌 Project Overview
The main goal of this project is to **practice data cleaning (wrangling) and data preparation** for training machine learning models.  
I  used the [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) as a case study.

---

## 🎯 Objectives
- Handle **missing values** (e.g., `country`, `children`, `agent`, `company`).
- Identify and remove **duplicates**.
- Detect and treat **outliers** using IQR.
- Create **new features** such as:
  - `Total_Guests` = `adults + children + babies`
  - `Total_Nights` = `stays_in_weekend_nights + stays_in_week_nights`
  - `ADR_per_Person` = `adr / Total_Guests`
  - `is_family` flag
- Encode **categorical variables**:
  - One-Hot Encoding for low-cardinality features (e.g., `meal`, `market_segment`, `deposit_type`, etc.).
  - Frequency Encoding & Grouping for high-cardinality features (e.g., `country`).
- Remove **data leakage columns** (`reservation_status`, `reservation_status_date`).
- Split data into **train/test sets** for further modeling.

---

## 🛠️ Tools & Libraries
- **Python** 🐍
- **Pandas** (data wrangling)
- **NumPy** (numerical operations)
- **Matplotlib & Seaborn** (visualization)
- **Scikit-learn** (encoding, splitting, scaling)

---

## 📊 Insights Explored
- Distribution of reservations by month.
- Most reserved room types.
- Cancellation rates by hotel type.
- Impact of deposit types on bookings.
- Total nights stayed distribution.
- Outliers in features like ADR, lead time, and guests.

---

## 🚀 Next Steps
- Train classification models to predict **reservation cancellation**.
- Perform feature importance analysis.
- Deploy results in a dashboard or web app.

---

## 👨‍💻 Author
This project was completed as a **practice exercise in data cleaning and preparation**. 
