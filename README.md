# 🛒 Olist E-Commerce Data Analysis (SQL + Python)
## Overview

This project analyzes the Olist E-Commerce Dataset, which contains nearly 100,000 orders from March 2016 to August 2018.
Olist is a Brazilian platform that connects small businesses to major online marketplaces.
The goal of this analysis is to gain insights into e-commerce trends in Brazil — from customer behavior and logistics performance to payment methods and seller distribution.

## 🧠 Objectives

Understand customer purchasing behavior and order frequency.

Analyze delivery performance and identify logistical bottlenecks.

Explore payment methods, installment trends, and revenue distribution.

Detect regional differences across Brazilian states.

Combine SQL for data extraction and Python for deeper analysis and visualization.

## ⚙️ Tools & Technologies

SQL (SQLite) — for data cleaning, joining, and aggregation.

Python (Pandas, Matplotlib, Seaborn) — for visualization and statistical analysis.

Jupyter Notebook — for interactive exploration and presentation.

## 📂 Dataset

The dataset was originally published by Olist on Kaggle.
<img width="3000" height="2325" alt="image" src="https://github.com/user-attachments/assets/7a1711a8-067e-4cf6-bf0b-4e025ced6fa2" />

It includes multiple tables:

orders — order lifecycle timestamps

customers — customer locations and IDs

order_items — product, seller, and price details

products — product categories and dimensions

sellers — seller IDs and locations

geolocation — coordinates of customers and sellers

payments — payment methods and installments

reviews — customer satisfaction feedback

## 🔍 Key Insights (examples)

Average delivery time vs expected delivery time across states.

Comparison of internal handling times between sellers.

Distribution of order values and installment counts.

Top performing states in total sales volume.

Correlation between review scores and delivery delays.

## 📈 Project Structure
📁 olist-ecommerce-analysis_sql-python
│
├── data/                     # Raw and cleaned datasets
├── sql/                      # SQL queries used for analysis
├── notebooks/                # Jupyter Notebooks (Python analysis)
├── visuals/                  # Charts and visualizations
├── README.md                 # Project documentation
└── requirements.txt          # Dependencies

## 🚀 How to Run

Clone the repository:

git clone https://github.com/alopezmoreira1989/olist-ecommerce-analysis_sql-python.git
cd olist-ecommerce-analysis_sql-python


(Optional) Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install dependencies:

pip install -r requirements.txt


Explore SQL queries or open Jupyter Notebooks to reproduce the analysis.

## 📊 Example Visuals

![top 10 items](https://github.com/user-attachments/assets/51c61d29-78d0-4950-b538-d73be01eaa99)
![order_distribution_non_delivered](https://github.com/user-attachments/assets/0209e480-1d3c-4765-b4b0-a0e87451483e)
![avg_delivery_times_delays_by_state](https://github.com/user-attachments/assets/ad6f8a25-bef1-43c7-a143-972edef7b2c4)
![order_status_by_year](https://github.com/user-attachments/assets/0b7483fb-b011-4623-b989-b9dd61201d14)
![Brazil_customers_sellers](https://github.com/user-attachments/assets/ad767294-35e1-4595-a640-c8a00e08a425)

## 🧩 Future Improvements

Automate SQL-to-Python data pipeline.

Build interactive dashboards with Plotly or Streamlit.

Extend the analysis to predict delivery delays using ML models.

## 🧾 License

This project is released under the MIT License.
Feel free to use, modify, and share it with attribution.
