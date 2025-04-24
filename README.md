
# 📊 SQL Data Analysis Project – Customer Spending Insights

This project uses **SQL Server** to analyze customer behavioral data, such as time spent on digital platforms and yearly expenditure. It includes table creation, data insertion, and analytical queries to provide business insights.

---

## 📁 Files Included

SQL QUERY: 

- Main SQL script to create the `customer` table, insert data, and run queries.

CUSTOMER DATA QUERY:

- Auto-generated script containing full `INSERT` statements for all rows from the CSV dataset.

DATASET: [data.csv](https://github.com/user-attachments/files/19888911/data.csv)

- : Original dataset with customer interaction data.
  

---

## 🧠 Features

- Table creation with columns: `Email`, `Address`, `Avatar`, `Time_on_App`, `Time_on_Website`, `Length_of_Membership`, `Yearly_Amount_Spent`.
- Full dataset insertion with manual and batch SQL queries.
- Creation of analytical views:
  - `avatar_info`: Aggregates customer count per avatar type.
- SQL queries to explore time spent on platforms vs. customer loyalty and spend.

---

## 🛠️ Tools Used

- SQL Server Management Studio (SSMS)

---

## 🚀 Getting Started

1. Open  in SSMS.
2. Execute the script to create and populate the table.
3. Run the view creation and analytical queries to explore insights


## ✅ Steps in SQLQuery3.sql
1. Create Table
A customer table is created with appropriate columns and data types:

Email, Address, Avatar, Time_on_App, Time_on_Website, Length_of_Membership, Yearly_Amount_Spent.

2. Insert Data
Multiple INSERT INTO statements populate the customer table with real data from a CSV file (converted into SQL format).

3. Create Views for Analysis
View : avatar_info

Groups customers by Avatar and counts how many use each type.

4. Aggregation & Grouping
Queries are used to explore:

Total number of users per avatar.

High spenders and their engagement levels.

5. Error Handling & Object Checks
Prior to creating views or tables, checks are added to:

Drop them if they already exist using IF OBJECT_ID(...) IS NOT NULL logic.

Ensure smooth script execution across multiple runs.

## Outcome

![Screenshot 2025-04-24 152838](https://github.com/user-attachments/assets/9b76a550-dd77-4969-bb78-ce0aaa7ff2bc)



![Screenshot 2025-04-24 152859](https://github.com/user-attachments/assets/580b0eaa-c165-44da-aff3-1e4bdae09bdc)

