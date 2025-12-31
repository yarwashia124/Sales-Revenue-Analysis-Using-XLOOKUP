# Sales-Revenue-Analysis-Using-XLOOKUP
An Excel project demonstrating XLOOKUP for calculating total revenue and finding the top sales rep.

# Sales Revenue Analysis Using XLOOKUP

## 📊 Project Overview
This project demonstrates how to analyze sales data across multiple departments using **Excel XLOOKUP**.
The goal is to identify the **top sales representative by total revenue** and their **region**.

## 📂 Data Sources
- **Transactions Sheet**: Sales transactions (RepID, ProductID, Quantity)
- **Reps Sheet**: Sales representative details (Name, Region)
- **Products Sheet**: Product pricing information

## ⚙️ Key Excel Skills Used
- XLOOKUP (Modern Excel)
- Cross-sheet data integration
- Revenue calculation
- Basic sales analysis

## 🧮 Core Formula Used
```excel
=Qty * XLOOKUP(ProductID, Products!A:A, Products!C:C)


🎯 Outcome

Calculated total revenue per transaction

Identified the top-performing sales representative

Mapped the sales region accurately

🛠 Tools

Microsoft Excel
