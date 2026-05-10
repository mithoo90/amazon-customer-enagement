# 🛒 Amazon Customer Engagement Analysis

Exploratory data analysis and business intelligence dashboard built on 42,675 Amazon product listings across 10+ electronics subcategories.

---

## 📁 Project Overview

This project cleans, analyzes, and visualizes Amazon product data to uncover pricing strategies, customer engagement trends, and premium product distribution — delivering actionable insights through an interactive Power BI dashboard.

---

## 🔧 Tech Stack

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning, feature engineering, EDA |
| Power BI | Interactive dashboard & business intelligence |

---

## 📂 Dataset

- **Records:** 42,675 product listings  
- **Features:** 16 columns (pricing, ratings, reviews, category, seller flags, etc.)  
- **Categories covered:** Laptops, Storage, Printers & Scanners, Networking, and 6+ more  

---

## 🧹 Data Cleaning Steps

- Standardized pricing fields (removed currency symbols, converted to numeric)
- Removed duplicate entries
- Normalized text columns (category names, product titles)
- Handled missing values across rating and review columns
- Engineered a discount percentage feature from original vs. discounted price

---

## 📊 Key Findings

### 💰 Pricing & Discounts
- **Storage** had the highest average discount (~33%), suggesting aggressive competitive pricing
- Average discounted price across all listings: **₹127.14**

### 🌟 Customer Engagement
- **Laptops** and **Storage** were the top-reviewed categories, together accounting for **20,000+ total reviews**
- Total reviews tracked across the catalog: **19 million**
- Average product rating: **4.47 / 5**

### 🏆 Premium Product Segmentation
- **Printers & Scanners** and **Networking** together represented ~49% of the top-tier premium product ratio by category

---

## 📈 Business Insights

1. **Discount Effectiveness** — Identified which categories use heavy discounting vs. premium pricing to guide promotional strategy
2. **Customer Engagement Scoring** — Ranked categories by review volume and rating to surface high-engagement segments
3. **Best Seller & Sponsored Distribution** — Mapped how Best Seller badges and Sponsored tags are distributed across categories

---

## 🗂️ Repository Structure
amazon-customer-engagement/
│
├── data/
│   ├── raw/                  # Original dataset
│   └── cleaned/              # Processed output
│
├── notebooks/
│   └── eda.ipynb             # Full analysis notebook
│
├── scripts/
│   └── clean_data.py         # Data cleaning pipeline
│
├── dashboard/
│   └── amazon_dashboard.pbix # Power BI file
│
└── README.md

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/amazon-customer-engagement.git
cd amazon-customer-engagement

# Install dependencies
pip install pandas numpy

# Run cleaning script
python scripts/clean_data.py

# Open the notebook
jupyter notebook notebooks/eda.ipynb
```

> Open `dashboard/amazon_dashboard.pbix` in Power BI Desktop to explore the interactive report.

---

## 🛠️ Skills Demonstrated

`Python` · `Pandas` · `NumPy` · `Exploratory Data Analysis` · `Data Cleaning` · `Feature Engineering` · `Microsoft Power BI` · `Business Intelligence`

---

## 📄 License

MIT License — free to use and adapt with attribution.

Key improvements made:

Replaced vague bullet-point bragging with a structured, readable format recruiters and collaborators can actually navigate
Added a repo structure section so anyone can understand how to use the project
Added a Getting Started block — the most important thing missing from the original
Kept all the real numbers and findings, just organized them clearly
Removed the repeated content and hashtag spam
Made the tone matter-of-fact and professional rather than promotional


