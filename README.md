# 📊 PhonePe Pulse Data Analysis
## 🚀 Project Overview

This project focuses on data harvesting, data warehousing, and visualization using PhonePe Pulse data. It extracts real-world digital payment data, processes it, stores it in a database, and presents insights through an interactive dashboard.

## 📌 Features
📥 Extract data from PhonePe Pulse (JSON format)

🧹 Data cleaning and transformation using Pandas

🗄 Store structured data in PostgreSQL

📊 Interactive visualizations using Plotly

🌐 Dashboard built with Streamlit

📍 State-wise and district-wise analysis

📅 Year and Quarter filtering

## 🛠️ Technologies Used
Python

Pandas

PostgreSQL

psycopg2

Streamlit

Plotly

JSON

## 📂 Project Structure

Phonepe/
│
├── pulse/                  # Raw JSON data
├── phonepe.py             # Streamlit dashboard
├── phonepeanalysis.ipynb  # Data processing notebook
├── README.md
└── requirements.txt

## 🔄 Data Pipeline
Extract JSON data from PhonePe Pulse

Process and clean data using Python

Convert into structured DataFrames

Store data in PostgreSQL tables

Query data for analysis

Visualize using Streamlit dashboard

## 🗄 Database Tables
aggregated_transaction

aggregated_user

map_transaction

map_user

top_transaction

top_user

## 📊 Dashboard Features
📌 Home Page

📌 Data Exploration

📌 Top Charts

📌 State Selection

📌 Quarter-wise Analysis

📌 District-level Insights

## 📈 Key Insights
Digital payments show steady growth over years

Top states contribute majority of transactions

Urban districts have higher app usage

Seasonal trends observed across quarters

## ⚠️ Challenges Faced
Handling nested JSON data

Data cleaning and normalization

Database connection errors

Streamlit rendering issues

## ✅ Solutions Implemented
Used structured loops for JSON parsing

Applied data transformation techniques

Added error handling

Optimized dashboard performance

## 🔮 Future Enhancements
Add predictive analytics

Deploy dashboard to cloud

Improve UI/UX design

Real-time data integration



⭐ If you like this project

Give it a ⭐ on GitHub!
