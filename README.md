# 🍽️  Data-Analysis-of-Zomato

## 📖 Description

This project analyzes Zomato restaurant and customer data to uncover patterns in ratings, cuisines, pricing, and regional trends. Using Python's data science stack (Pandas, Matplotlib, NumPy, Seaborn, Plotly), it provides actionable insights for business strategy, customer preferences, and restaurant segmentation.

## 📌 Project Overview

This project analyzes Zomato data through:

✔ Exploratory Data Analysis (EDA)

✔ Feature Engineering

✔ Statistical Summaries

✔ Probability-Based Insights

✔ Interactive Visualizations

## 📂 Dataset

Source: zomato.csv (Custom Dataset)

## Key Features (Typical Columns):

name → Restaurant name

online_order → Availability of online ordering (Yes/No)

book_table → Availability of table booking (Yes/No)

rate → Restaurant rating (e.g., 3.9/5)

votes → Number of votes

location → Area/City of restaurant

cuisines → Cuisines served

listed_in(city) → City tag

## 📊 Analysis Highlights

Distribution of Ratings count :

<img width="1014" height="525" alt="image" src="https://github.com/user-attachments/assets/d7923f96-2def-4bd0-9583-94fc6257075e" />

Top 5 cities:

<img width="528" height="482" alt="image" src="https://github.com/user-attachments/assets/36eed64c-1dd0-40ae-ac09-ab3d7e067e24" />

## 📌 Conclusion & Insights

✔ Customer Preferences:

Customers strongly prefer restaurants that support online orders and table booking, showing the rising importance of digital convenience in the food industry.

Ratings are skewed towards average to good (3.5–4.5 range), meaning customers are moderately satisfied but selective.

✔ Regional Trends:

Top 5 cities dominate the restaurant landscape, indicating higher competition and customer diversity in metropolitan areas.

Location plays a significant role in determining popularity, with central city areas having better ratings and engagement.

✔ Cuisine Analysis:

Multi-cuisine restaurants are more popular and receive higher votes compared to single-cuisine outlets.

Popular cuisines such as North Indian, Chinese, and Italian appear frequently in high-rated restaurants.

✔ Business Strategy Insights:

Restaurants with higher votes & consistent ratings build stronger customer trust.

Online platforms and discounts can help smaller restaurants compete with established ones.

Targeting fast-growing urban regions could maximize market reach.

👉 Overall, the Zomato dataset reveals that customer convenience (online order, table booking), regional dynamics, and cuisine diversity are the key drivers of restaurant success.

## 📦 Requirements

pip install pandas numpy matplotlib seaborn plotly jupyter

## ▶️ Run
jupyter notebook Zomato_Data_Analysis.ipynb
