# Airport_Data_Analysis
Airport Data Analysis uses the Meta_Data file to build a relational database in MySQL. It cleans and organizes flight, airline, passenger,and freight, ensuring accuracy through deduplication and validation. The project enables efficient queries and insights into aviation trends.

# ✈️ Airport Data Analysis  

## 📌 Overview  
The **Airport Data Analysis** project focuses on analyzing flight and airline operations using the provided `Meta_Data` file. The dataset contains information about airlines, passengers, freight, mail, routes, and time-based attributes such as year, month, and quarter.  

This project organizes the raw data into a structured **MySQL relational database**, making it easier to query, analyze, and gain insights into aviation trends.  

---

## 🗂️ Key Features  
- 📊 **Data Cleaning & Validation** – handled missing values, duplicates, and inconsistencies.  
- 🛫 **Airline & Flight Tables** – structured schema for airlines, flights, and metrics.  
- 🔗 **Relational Database Design** – implemented foreign keys to connect different entities.  
- 📈 **Analytical Queries** – supports insights such as busiest routes, freight/mail trends, and seasonal patterns.  

---

## 🏗️ Database Structure  
- **Airline** → Stores airline details (ID, carrier code, carrier name).  
- **Flight** → Stores flight routes with origin, destination, and time details.  
- **FlightMetrics** → Contains passengers, freight, and mail data linked to each flight.  

---

## ⚙️ Implementation Highlights  
- Used `INSERT IGNORE` and `ON DUPLICATE KEY UPDATE` to handle duplicate records.  
- Replaced invalid numeric values (e.g., freight/mail) with `NULL` to prevent errors.  
- Ensured data integrity with proper keys and constraints.  

---

## 🔍 Example Queries  
- Find the busiest routes by passenger traffic.  
- Analyze freight and mail trends by region.  
- Compare airline performance using unique carrier codes.  
- Identify seasonal travel patterns by quarter and year.  

---

## 🎯 Goal  
The project transforms raw aviation metadata into a **clean, reliable, and query-ready database**. It demonstrates data cleaning, schema design, and SQL analysis, making it a helpful resource for students, researchers, and aviation analysts.  

---
