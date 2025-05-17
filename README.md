# 🧾 MySQL Data Visualization Project

This project connects to a MySQL database named `shop_management` and generates three data visualizations using `pandas`, `matplotlib`, and `seaborn`. It is ideal for demonstrating basic SQL-to-Python data integration and visual reporting skills.

## 📦 Project Overview
This script performs the following:

1. **Connects to a local MySQL database**
2. **Queries data from multiple related tables**
3. **Visualizes the data using bar plots, pie charts, and line plots**

## 📊 Visualizations

### 1. Number of Orders per Customer
A bar chart showing how many orders each customer has placed.

### 2. Coupon Usage by Type
A pie chart representing how often different types of coupons are used.

### 3. Daily Order Count
A line chart showing the number of orders made on each date.

## 🧰 Technologies Used
- Python 3.x
- MySQL
- pandas
- matplotlib
- seaborn
- mysql-connector-python

## 🗂️ Database Tables Involved
- `CUSTOMER`
- `ORDER`
- `COUPON`
- `ORDERCOUPON`

## 🚀 How to Run
1. Make sure your MySQL server is running and the `shop_management` database is available.
2. Update the database credentials in the script if needed.
3. Run the script:
```bash
python mysql_analysis_charts.py
```
4. View the generated charts in the output window.

## 📸 Suggested Screenshots for GitHub
- Screenshot of each chart
- Optional: A sample of the terminal output showing successful connection

## 📄 License
This project is for educational and portfolio purposes.

---
Feel free to customize and expand the queries or visuals to reflect deeper analysis!
