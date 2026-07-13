# 🚗 Used Car Price Analytics Dashboard

> **Interactive Tableau dashboards analyzing 550,000+ used car listings** to help a new auto dealer make data-driven decisions in a competitive market.

---

## 📌 Project Overview

This project builds three interactive Tableau dashboards on a dataset of **550,000+ used car listings**, answering key business questions around pricing strategy, market competition, and future trends.

**Business Question:**  
*How can a new auto dealer make data-driven decisions to succeed in a competitive used car market?*

---

## 📊 Dashboards

### Dashboard 1 — Car Sales at a Glance: Volume, Regions & Preferences
- **Total Cars Sold:** 9,149
- **Avg Selling Price:** $9,431
- **Avg Odometer:** 94,588 miles
- Interactive **map of average selling price by U.S. state** ($2,800–$15K range)
- Filter by **color** and **transmission type** (automatic vs manual)
- **Insight:** Location influences pricing due to local demand, taxes, and buyer income

### Dashboard 2 — What Drives the Price? Exploring Factors Behind Car Value
- **Top brands by avg price:** Mercedes-Benz & BMW lead at $20–22K
- **Condition vs price:** Price drops sharply as condition deteriorates
- **Odometer vs selling price scatter:** High mileage sharply reduces value even in good condition
- **MMR vs selling price:** Strong positive correlation with profit margin overlay
- **Insight:** Brand and mileage outweigh condition — luxury brands command premium prices regardless

### Dashboard 3 — Market Movers: Top Sellers & Price Forecasts
- **Top 15 sellers:** Ford Motor Credit leads at ~$330M in selling price
- **Price forecast (1995–2040):** Actual trend + estimated forecast band
- Market projected to reach **$10B+ by 2040**
- Filter by **Year** and **Top N** sellers
- **Insight:** The used car market is a high-growth sector with strong consolidation among top institutional sellers

---

## 🔍 Key Insights

| Factor | Finding |
|---|---|
| 🏷️ **Brand** | Mercedes-Benz & BMW avg $20–22K — luxury brand is the #1 price driver |
| 📍 **Location** | State avg ranges from $2,800 to $15K — regional variance is significant |
| 🔧 **Mileage** | Every 100K miles on odometer sharply reduces value |
| 📈 **Market Growth** | Used car market forecast to hit $10B+ by 2040 |
| 🏢 **Competition** | Ford Motor Credit dominates at ~$330M — top 3 sellers hold outsized share |

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Tableau** | Dashboard development, interactive filters, forecasting |
| **SQL** | Data querying and aggregation |
| **Python** | Data cleaning and preprocessing |
| **Regression Analysis** | Price prediction modeling |
| **Forecasting** | Time-series price forecast (1995–2040) |

---

## 📁 Repository Contents

```
├── Used_Car_Analytics.twbx     # Tableau packaged workbook (all 3 dashboards)
├── README.md                   # Project documentation
└── screenshots/
    ## 📸 Dashboard Screenshots

```
### Dashboard 1 — Sales Overview
<img width="1470" height="956" alt="Screenshot 2026-07-13 at 15 37 35" src="https://github.com/user-attachments/assets/c5bff02d-b381-4d3d-8ba0-6751b942bc13" />


### Dashboard 2 — Price Factors  
<img width="1470" height="956" alt="Screenshot 2026-07-13 at 15 37 43" src="https://github.com/user-attachments/assets/88366836-cbdf-4a91-b8ed-9cc498f83cb5" />


### Dashboard 3 — Market Movers
<img width="1470" height="956" alt="Screenshot 2026-07-13 at 15 37 54" src="https://github.com/user-attachments/assets/df4f1bbb-7b1a-4849-843d-4ce8967dd47e" />



---

## 🚀 How to Open

1. Download **Tableau Public** (free) from [public.tableau.com](https://public.tableau.com)
2. Open `Used_Car_Analytics.twbx`
3. Use the dashboard tabs at the bottom to navigate between the 3 views
4. Use filters (Year, Top N, Color, Transmission) to explore interactively

---

## 📂 Dataset

**Source:** Used Car Dataset — Kaggle  
**Records:** 550,000+ listings  
**Key Fields:** Make, Model, Year, Condition, Odometer, Selling Price, MMR, Seller, State, Color, Transmission

---

## 👤 Author

**Jinay Jain**  
MS Business Analytics · Syracuse University  
📧 jinayjjain@gmail.com  
🔗 [linkedin.com/in/jijain](https://linkedin.com/in/jijain)  
🌐 [jinay0031.github.io](https://jinay0031.github.io)
