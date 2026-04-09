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

Install dependencies:

Database Configuration:

Run the scripts in queries.sql on your SQL Server.

Update the connection string in app.py with your credentials.

Run the App:

Detailed Project Description
The Product Stock Management System is a full-stack data application designed to streamline inventory control for small to medium-sized businesses.

Unified Data Management: All product information is stored in a structured relational database, ensuring data consistency and preventing duplicate entries.

Real-Time CRUD Operations:

Create: Add new product lines to the warehouse.

Read: Fetch instant details about specific items or categories.

Update: Modify stock levels immediately after a sale or restock.

Delete: Remove discontinued items while maintaining database integrity.

Dynamic Data Visualization: Transforms raw SQL tables into visual insights, including low-stock alerts and inventory overviews.

Dataset
The dataset used for this project involves product IDs, stock counts, and categories.

Access Dataset Folder
[Dataset](https://drive.google.com/drive/folders/1kljwTgtYbMZ-Qu3Sz_ZYlHZsgcSEzW-j?usp=sharing)







