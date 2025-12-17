📊 Customer Data Analysis & Dashboard Report
📌 Project Overview

This project demonstrates how to connect a MySQL database with Jupyter Notebook, perform data extraction, transformation, and analysis, and build an EDA-based dashboard report.
The goal is to analyze customer-related data from an e-commerce database and generate meaningful insights using Python.

🛠️ Technologies Used

Python

Jupyter Notebook

MySQL

Pandas

SQLAlchemy

MySQL Connector

Matplotlib / Seaborn (for visualization)

📂 Project Structure
├── customer_EDAREPORT.ipynb   # Jupyter Notebook with MySQL connection, EDA & dashboard
├── README.md                 # Project documentation

🔗 Database Connection

The notebook connects to a MySQL database using mysql-connector-python and SQLAlchemy.

Sample Connection Code:
import mysql.connector

connection = mysql.connector.connect(
    host="localhost",
    user="root",
    password="Root",
    database="Ecom"
)

📥 Data Ingestion

Data is fetched from MySQL tables using SQL queries

Records are loaded into Pandas DataFrames

Supports both single-row and bulk inserts from Jupyter Notebook

📊 Exploratory Data Analysis (EDA)

The following analysis was performed:

Data cleaning and preprocessing

Handling missing values

Statistical summaries

Customer behavior analysis

Trend identification

📈 Dashboard & Visualizations

An interactive dashboard was created to visualize:

Customer distribution

Product/category insights

Sales trends

Quantity and pricing patterns

Visualizations include:

Bar charts

Line graphs

Pie charts

Summary tables

✅ Key Outcomes

Successfully integrated MySQL with Jupyter Notebook

Automated data insertion and retrieval

Built a structured EDA dashboard

Generated actionable insights from raw database data

🚀 How to Run the Project

Install required libraries:

pip install mysql-connector-python pymysql sqlalchemy pandas matplotlib seaborn


Start Jupyter Notebook:

jupyter notebook


Open:

customer_EDAREPORT.ipynb


Update database credentials if needed

📌 Future Enhancements

Add Streamlit / Power BI dashboard

Connect to AWS RDS MySQL

Automate report generation

Apply machine learning models

👩‍💻 Author

Sowmya Potu
Master’s in Computer Science
Java Full Stack & Data Analysis Enthusiast

🔗 GitHub: https://github.com/Sowmyapotu2001

🔗 LinkedIn: https://www.linkedin.com/in/sowmya-potu-70815117b/
