# SQL_DataBase_Creation_For_Retail_Store

## 📌 Overview  
This project demonstrates the creation of a comprehensive relational database system for a retail store, focusing on **Sales** and **Production** operations. It includes SQL scripts, an ER diagram, and a project presentation that outlines the data model and relationships between entities.

## 🎯 Project Objective  
To design and implement a normalized, scalable SQL database that supports key business processes such as inventory tracking, order fulfillment, and product management. The database integrates **Sales** and **Production** modules, simulating a real-time business scenario.

## 🗂️ Database Structure  
The system consists of two interconnected schemas:
- **Sales**: `Customers`, `Orders`, `OrderItems`, `Stores`, `Staff`
- **Production**: `Products`, `Brands`, `Categories`, `Stocks`

## 🛠️ Key Features  
- Structured schema with **primary and foreign key constraints**  
- **Normalized tables** using appropriate data types (`INT`, `VARCHAR`, `DECIMAL`)  
- **Join operations** between sales and production for meaningful analysis  
- Data integrity enforced via relational constraints

## 🔍 Sample Relationships  
- `OrderItems.product_id` → `Products.product_id`  
- `Stocks.store_id` → `Stores.store_id`  
- Joined queries combining sales and inventory details for unified reporting

## ✅ Learning Highlights  
- Built SQL database from scratch using `MySQL Workbench`  
- Created ER diagrams to define and visualize relationships  
- Practiced multi-table **JOINs**, **normalization**, and **data linking**  
- Gained experience in **modular database design** suitable for business use cases

---

📂 Files included:
- `Final Project.sql` – SQL script with table creation and schema definitions  
- `ER Diagram Final.mwb` – Entity-Relationship diagram  
- `SQL Final Presentation.pptx` – Summary presentation of the database

