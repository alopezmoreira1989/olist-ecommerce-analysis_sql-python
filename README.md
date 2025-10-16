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

The dataset was originally published by Olist on Kaggle
.
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

(Add screenshots or charts here — e.g. delivery time by state, payment trends, etc.)

## 🧩 Future Improvements

Automate SQL-to-Python data pipeline.

Build interactive dashboards with Plotly or Streamlit.

Extend the analysis to predict delivery delays using ML models.

## 🧾 License

This project is released under the MIT License.
Feel free to use, modify, and share it with attribution.
