# Food_Products_Company_DWH



#Northwind Traders Data Warehouse Project

This project demonstrates the design and implementation of a **Data Warehouse** for a specialty food import/export company.  
It follows **Kimball’s Dimensional Modeling Approach**, using **Star Schema** design, SQL for ETL & analytics, and dashboards converted to images.

---

## 📌 Business Context
The company manages thousands of orders across diverse product lines, regions, and customer segments.  

Core operations include:
- **Sales Operations**
- **Logistics Management**

---

## 🗂️ Data Warehouse Design
- **Facts**: Sales, Logistics, Supply Chain  
- **Dimensions**: Products, Categories, Suppliers, Customers, Employees, Regions, Shippers, Date & Time

### 🖼️ Design & Architecture
![DrawSQL Diagram](assets/drawSQL-image-export-2025-11-11.png)  
![Architecture](assets/Architecture.jpeg)

---

## 🔹 Implementation Strategy
1. **Staging Area** – raw data ingestion  
2. **Data Profiling** – quality assessment & pattern discovery  
3. **Data Cleaning & Handling** – standardization, deduplication, error correction  
4. **Facts & Dimensions** – structured modeling in SQL  
5. **Business Questions** – analytics-ready dataset for decision-making  

---

## 📊 Business Insights (via dashboards)
- Sales trend analysis (monthly & quarterly)  
- Top 10 products by revenue  
- Regional customer performance  
- Profit margin and discount impact  
- Shipper performance & delivery times  
- Customer segmentation and purchasing behavior  

### Dashboards
![Dashboard 1](assets/1.png)  
![Dashboard 2](assets/2.png)  
![Dashboard 3](assets/3.png)

---

## 🚀 Technologies
- **SQL** for data modeling, ETL, and querying  
- **Dashboards (images)** for visualization  
- **Kimball’s methodology** for DWH design
