# 📊 Project 1 — Data Cleaning & Preparation

## 📌 Objective
Clean a raw e-commerce dataset by handling missing values, 
duplicates, and incorrect data formats.

---

## 📁 Dataset Info
- **File:** Dataset for Data Analytics.xlsx
- **Rows:** 1200
- **Columns:** 14
- **Domain:** E-commerce Orders

### Columns:
| Column | Description |
|--------|-------------|
| OrderID | Unique order identifier |
| Date | Order date |
| CustomerID | Customer identifier |
| Product | Product purchased |
| Quantity | Number of items |
| UnitPrice | Price per item |
| ShippingAddress | Delivery address |
| PaymentMethod | Payment type used |
| OrderStatus | Current order status |
| TrackingNumber | Shipment tracking |
| ItemsInCart | Cart item count |
| CouponCode | Discount coupon used |
| ReferralSource | Marketing channel |
| TotalPrice | Final order amount |

---

## 🧹 Cleaning Steps Performed

### 1. Missing Values
- Found **309 missing values** in CouponCode column
- Filled with **"No Coupon"**

### 2. Duplicate Rows
- Found **0 duplicates** ✅

### 3. Data Types
- Date column verified as `datetime64`
- Numeric columns verified correctly

### 4. Text Cleaning
- Removed extra spaces from Product,
  OrderStatus, PaymentMethod columns

---

## ✅ Result
- **Input:** Raw dataset (1200 rows)
- **Output:** Cleaned_Dataset.xlsx
- **Issues Fixed:** 309 missing values, text formatting

---

## 🛠️ Tools Used
- Python 3
- Pandas
- NumPy
- Jupyter Notebook

---

## 👩‍💻 Author
Shivika — Data Analyst Intern @ Decode Lab
