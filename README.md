# 🛒 E-commerce Sales & Delivery Performance Dashboard

##  Project Overview

This project focuses on analyzing an e-commerce dataset to uncover insights related to **sales performance, customer behavior, and delivery efficiency**.

The goal is to transform raw, messy data into a **business-ready dataset** and build a **single-page, insight-driven Power BI dashboard**.

##  Objectives

* Perform **data cleaning and preprocessing**
* Merge multiple datasets into a unified structure
* Create **meaningful business metrics**
* Analyze **revenue trends, product performance, and delivery efficiency**
* Build a **clean, professional dashboard with actionable insights**


##  Dataset

* Source: Olist Brazilian E-commerce Dataset (Kaggle)
* Includes:

  * Orders
  * Customers
  * Products
  * Order Items
  * Payments


##  Data Cleaning & Preprocessing

Key steps performed:

* Converted date columns to proper datetime format
* Handled missing values intelligently (e.g., delivery status logic)
* Removed unnecessary columns to optimize performance
* Created new features:

  * Revenue
  * Delivery Days
  * Delivery Status
  * Month & Year
* Removed outliers (top 1% revenue) to improve analysis accuracy


##  Data Modeling

* Merged multiple tables using:

  * `order_id`
  * `customer_id`
  * `product_id`
* Created a **flattened dataset** for efficient analysis in Power BI



##  Key Insights

* A significant portion of revenue is linked to **delayed deliveries**, indicating operational inefficiencies
* Certain product categories contribute heavily to total revenue, showing **category dependency**
* Delivery delays impact overall business performance and customer experience


##  Tools & Technologies

* Python (Pandas, NumPy)
* Jupyter Notebook
* Power BI
* DAX

##  Conclusion

This project demonstrates the ability to:

* Work with real-world messy data
* Perform end-to-end data analysis
* Build business-focused dashboards
* Extract actionable insights

## Preview Images

**Overview** - https://github.com/Christopher-AR/E-Commerce-/blob/main/Overview.png

**Filtered via Year Slicer (2017)** - https://github.com/Christopher-AR/E-Commerce-/blob/main/Filtered%20via%20Year%20Slicer%20(2017).png 

**Filtered via Year & Product Category Slicer** - https://github.com/Christopher-AR/E-Commerce-/blob/main/Filtered%20via%20Year%20%26%20Product%20Category%20Slicer.png


##  Connect With Me

If you found this project useful or have feedback, feel free to connect!
