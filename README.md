# 🚗Automobile Market Analytics MySQL

## 📌Project Overview

This project analyzes a used car marketplace dataset using MySQL. The main goal is to clean the data, perform Exploratory Data Analysis (EDA) and discover useful insights about vehicle prices, specifications, and market trends.

---

## Objectives

- Clean the dataset 
- Handle missing and inconsistent values.
- Perform Exploratory Data Analysis (EDA).
- Answer real business questions using SQL.
- Practice SQL skills for a data Analyst portfolio.

---

## 🗒️Dataset

The dataset contains information about used vehicles, including :
- Make
- Model
- Year
- Fuel_Type
- Transmission
- Engine_Size
- Mileage
- Horsepower
- Torque
- Owners
- Accident_History
- Service_History
- Color 
- Body_Type
- Drivetrain
- Fuel_Efficiency
- Location
- Selling_Price

---

## 🧹Data Cleaning

The following cleaning steps were performed :

- Removed duplicate records.
- Checked for NULL values.
- Replaced empty text values with 'Unknown'.
- Verified numeric columns.
- Created a clean table for analysis

---

## 🔎Exploratory Data Analysis (EDA)

The project answers questions such as :

- How many records are in the dataset ?
- Which car brands have the highest average selling price ?
- What are the top 10 most expensive cars ?
- Which brand appears most frequently ?
- What is the average selling price by fuel type ?
- Which cars have the highest torque ?
- Is there a relationship between horsepower and selling price ?
- How does accident history affect selling price ?
- How does Service history affect selling price ?
- How does the number of previous owners affect selling price ?
- How does mileage vary across manufacturing years ?
- Which location has the most listed vehicles ?
- What is the distribution of vehicles by fuel type ?
- What is the distribution of vehicles by transmission ?
- What is the distribution of vehicles by body type ?
- Which brand offers the best fuel efficiency ?
- Which cars provide the best fuel efficiency relative to engine size ?

---

## 📊SQL concepts Used 

- SELECT
- WHERE 
- GROUP BY
- ORDER BY
- LIMIT
- COUNT()
- SUM()
- AVG()
- MAX()
- MIN()
- ROUND()
- DISTINCT
- CASE
- Aliases (AS)

---

## 🎯Key Insights

- SUVs are the most common vehicle type.
- Petrol vehicles dominate the dataset.
- Automatic transmission is more common then manual.
- Selling price is influenced by multiple vehicle characteristics such as year, mileage, horsepower, and engine size.
- Fuel efficiency varies significantly across different brands and models.

---

## Project Structure

```
01_database_setup.sql
02_data_cleaning.sql
03_clean_table_and_eda.sql
README.md
```

## 🛠️Tools Used

- MySQL Workbench
- SQL

---

## 💡Results

- Analyzed car selling prices across different fuel types and transmission categories.
- Explored the relationship between mileage, manufacturing year, and selling price.
- Examined how horsepower and torque relate to vehicle prices.
- Compared selling prices based on ownership history and accident history.
- Investigated the impact of service history on car selling prices.
- Performed exploratory data analysis (EDA) using SQL queries to identify patterns and relationships in the automobile market.

---

## ✔️Conclusion 

This project used MySQL to explore automobile market data analyze the factors associated with car selling prices. The analysis focused on vehicle specifications, mileage, manufacturing year, ownership history, accident history, and service records.

Through data cleaning, SQL queries, and exploratory data analysis, I strengthened my skills in data preparation, data aggregation, filtering, and analytical problem-solving.

The project demonstrates how SQL can be used to explore automotive data, identify market patterns, and support data-driven insights into vehicle pricing.

## Author

Anis Mo
