# E-commerce Product Review & Rating Analysis

> **Course Project** | Data Analysis | Ho Chi Minh City University of Industry and Trade (HUIT)
> **Role:** Team Leader | **Team size:** 3 members | **Period:** Oct 2025 – Jan 2026

---

## Project Overview

This project analyzes customer reviews and product ratings from **TechStyle Online Ltd.** — an international e-commerce company based in Toronto, Canada — to uncover the relationship between customer feedback and business revenue performance.

**Dataset:** 3 linked tables — Products, Reviews (ratings + text), Sales (monthly revenue)
**Key metrics tracked:** $3.86M revenue · 180 orders · 159 reviews

---

## Objectives

- Analyze rating distributions and identify products with low satisfaction
- Perform **NLP Sentiment Analysis** on review text to classify customer emotions
- Investigate the correlation between ratings/sentiment and revenue
- Propose data-driven business strategies based on findings

---

##  Tools & Technologies

| Tool | Usage |
|------|-------|
| **Power BI** | Data cleaning (Power Query), Star Schema modeling, DAX measures, Dashboard |
| **Python** | NLP Sentiment Analysis (VADER), Heatmap, Boxplot, Correlation matrix |
| **Libraries** | `pandas`, `nltk`, `vaderSentiment`, `matplotlib`, `seaborn` |

---

## Key Findings

### 1. Sentiment Distribution
- **44.65%** Positive reviews
- **17.61%** Neutral reviews  
- **37.74%** Negative reviews

### 2. Device-based UX Drop 
Tablet devices showed a critically low average rating of **2.71★** compared to **3.8★** on Desktop — indicating a significant UI/UX issue on tablet interfaces.

### 3. Revenue Paradox
Some best-selling products had the lowest ratings — signaling a risk of customer churn if satisfaction issues go unaddressed.

---

## Dashboard Features

- **Overview Dashboard:** KPI cards (Revenue, Orders, Reviews), Rating distribution, Revenue by category
- **Drill-through Dashboard:** Product-level deep dive, Device-type breakdown, Time-trend analysis
- **Python Visuals (embedded in Power BI):**
  - Correlation heatmap between numeric variables
  - Sentiment analysis bar chart
  - Revenue distribution boxplot by category

---

## Business Recommendations

1. **Real-time Alert System** — Power BI alert workflow routing 1–3 star reviews to customer service within **2 hours** for immediate follow-up
2. **"Mid-year Review Festival"** campaign in June–July to recover engagement dips identified in trend data
3. **Tablet UX Optimization** — Prioritize mobile/tablet interface improvements for categories with lowest device ratings
4. **Targeted improvement** for high-revenue / low-rating products to reduce future churn risk

---

##  Repository Contents

```
 ecommerce-review-rating-analysis
├── Nhom6_DoAn.pbix        # Power BI dashboard file
└── README.md
```

>  To open the `.pbix` file, download and open with [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).

---

##  Author

**Dinh Le Tien Thanh** — E-commerce Student, HUIT
- 🔗 [LinkedIn](https://www.linkedin.com/in/tienthanh1103/)
- 📧 thanhneymar110305@gmail.com
