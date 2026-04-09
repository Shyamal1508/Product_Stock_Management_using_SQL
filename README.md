Product Stock Management System
An end-to-end stock management application that bridges a SQL Server backend with a Streamlit web interface. This tool allows businesses to track inventory levels, manage product metadata, and visualize stock trends in real-time.

Project Demo
[Demo](https://drive.google.com/file/d/1ptbbgETdrg8ocef4K4tUiDr9J-GVCC09/view?usp=sharing)


Key Features
Real-time Synchronization: Direct connection between Python and SQL for instant database updates.

Inventory Tracking: Add, update, or delete products with automated stock level monitoring.

Dynamic Dashboards: Visual representation of stock availability using Streamlit components.

SQL Backend: Structured relational database for data integrity and complex querying.

Tech Stack
Frontend: Streamlit (Python)

Database: SQL Server / MySQL

Data Handling: Pandas, SQLAlchemy/pyodbc

Project Structure
app.py: Main Streamlit application file.

queries.sql: SQL scripts used for table creation and stored procedures.

requirements.txt: Necessary libraries to run the project.

Installation and Setup
Clone the repository:
https://www.google.com/search?q=https://github.com/Shyamal1508/Product_Stock_Management_using_SQL.git

Install dependencies:
pip install -r requirements.txt

Database Configuration:

Run the scripts in queries.sql on your SQL Server.

Update the connection string in app.py with your credentials.

Run the App:
streamlit run app.py

📝 Detailed Project Description
The Product Stock Management System is a full-stack data application designed to streamline inventory control for small to medium-sized businesses. It replaces manual spreadsheet tracking with a centralized SQL database and a high-performance Python interface.

1. Unified Data Management
The system acts as a "Single Source of Truth." Instead of scattered files, all product information—including IDs, descriptions, pricing, and real-time stock counts—is stored in a structured relational database. This ensures data consistency and prevents errors like duplicate entries or lost records.

2. Real-Time CRUD Operations
The application allows users to perform core database actions directly through the web UI without writing a single line of code:

Create: Add new product lines to the warehouse.

Read: Fetch instant details about specific items or categories.

Update: Modify stock levels immediately after a sale or restock.

Delete: Remove discontinued items while maintaining database integrity.

3. Dynamic Data Visualization
Using the power of Streamlit, the project transforms raw SQL tables into visual insights. It includes:

Low-Stock Alerts: Automatically highlights items that fall below a certain threshold to prevent out-of-stock scenarios.

Inventory Overview: A birds-eye view of total stock value and quantity across different categories.

4. The Technical Bridge
The core value of this project lies in its Integration Logic. It demonstrates how to securely connect a Python application to an external SQL Server using connection strings and executing optimized queries to ensure the application remains fast even as the dataset grows.

Dataset
The dataset used for this project involves product IDs, stock counts, and categories.

Access Dataset Folder
[Dataset](https://drive.google.com/drive/folders/1kljwTgtYbMZ-Qu3Sz_ZYlHZsgcSEzW-j?usp=sharing)







