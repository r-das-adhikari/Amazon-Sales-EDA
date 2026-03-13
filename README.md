# Amazon Sales EDA 🛒
Exploratory Data Analysis on Amazon India Sales dataset (128,835 rows).

## 📊 Analysis Covers
- Sales & Revenue Trends
- Category & Product Analysis
- Geographic Analysis (State & City)
- Cancellation Analysis

## 🧹 Data Cleaning
- Fixed column names (stripped spaces, title case)
- Converted Date to datetime format
- Cast categorical and numeric columns to correct data types
- Mapped 13 order statuses into 5 clean categories (Delivered, In Progress, Pending, Cancelled, Returned)
- Fixed inconsistent state names (Rajshthan → Rajasthan, Orissa → Odisha, etc.)
- Filled null values (Amount filled with category median, Fulfilled_By, Currency, Promotion_Ids)
- Removed rows where Qty = 0 and order was not Cancelled
- Cleaned postal codes (removed decimals, zero-padded to 6 digits)
- Created Promotion_Type column from raw Promotion_Ids

## 🛠️ Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn

## 📁 Dataset
Amazon Sale Report — India (Mar–Jun)
