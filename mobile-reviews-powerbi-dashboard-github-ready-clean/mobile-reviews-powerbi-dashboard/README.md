# Mobile Reviews Sentiment Analysis - Power BI Dashboard

## Project Overview

This project is a Power BI dashboard built to analyze 50,000 mobile phone customer reviews.

The dashboard focuses on customer sentiment, brand performance, product ratings, pricing, customer behavior, and review trends. The goal is to turn raw review data into useful insights that can support product and business decisions.

The report contains three main pages:

- Executive Overview
- Product Analysis
- Customer Insights

---

## Dashboard Pages

### 1. Executive Overview

This page provides a high-level summary of customer reviews and overall market performance.

Main metrics and visuals include:

- Total Reviews
- Average Customer Rating
- Average Price
- Positive Reviews
- Verified Purchase Percentage
- Customer Sentiment Distribution
- Average Rating by Brand
- Review Volume by Brand
- Review Volume Over Time

### 2. Product Analysis

This page focuses on product performance, pricing, and feature-level ratings.

Main visuals include:

- Price vs Rating by Model
- Sentiment by Price Segment
- Average Rating by Price Segment
- Feature Ratings by Brand
- Battery Life Rating
- Camera Rating
- Performance Rating
- Design Rating
- Display Rating

### 3. Customer Insights

This page looks at customer behavior, geography, purchase verification, and review platforms.

Main visuals include:

- Review Helpfulness by Sentiment
- Verified vs Non-Verified Purchase Rating
- Customer Rating by Age Group
- Review Volume by Platform
- Sentiment Distribution by Country
- Verified Purchase Percentage
- Average Rating
- Total Reviews
- Positive Review Percentage

---

## Dataset

The dataset contains 50,000 customer reviews with 25 columns.

| Metric | Value |
|---|---:|
| Total Reviews | 50,000 |
| Brands | 7 |
| Models | 22 |
| Countries | 8 |
| Review Platforms | 5 |
| Average Rating | 3.12 / 5 |
| Verified Purchases | 80.14% |
| Date Range | Oct 2022 - Oct 2025 |

### Brands Included

Apple, Google, Motorola, OnePlus, Realme, Samsung, and Xiaomi.

### Review Platforms

Amazon, Flipkart, AliExpress, BestBuy, and eBay.

### Main Fields

- Customer information: customer name, age, country, language
- Product information: brand, model, price
- Review information: rating, review text, sentiment, review date
- Purchase information: verified purchase
- Feature ratings: battery life, camera, performance, design, display
- Engagement information: helpful votes, review length, word count
- Review source

---

## Key Findings

- 55.1% of reviews are positive.
- 25.1% of reviews are neutral.
- 19.8% of reviews are negative.
- The average customer rating is approximately 3.12 out of 5.
- Around 80.14% of reviews are from verified purchases.
- Brand and model comparisons help identify differences in customer satisfaction and pricing.
- Feature-level ratings provide more detail than the overall star rating alone.
- Country and platform analysis make it possible to compare customer feedback across different markets.

---

## Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- CSV
- GitHub

---

## Skills Demonstrated

- Data cleaning and transformation
- Data modeling
- DAX measures
- KPI creation
- Interactive filters and slicers
- Sentiment analysis
- Time-series analysis
- Brand and product comparison
- Customer segmentation
- Dashboard design
- Data visualization
- Business-focused analysis

---

## Repository Structure

```text
mobile-reviews-powerbi-dashboard/
│
├── README.md
├── .gitignore
│
├── dashboard/
│   └── Mobile_Reviews_PowerBI_Dashboard.pbix
│
├── data/
│   └── Mobile_Reviews_Sentiment.csv
│
└── screenshots/
    ├── executive-overview.png
    ├── product-analysis.png
    └── customer-insights.png
```

---

## Dashboard Preview

### Executive Overview

![Executive Overview](screenshots/executive-overview.png)

### Product Analysis

![Product Analysis](screenshots/product-analysis.png)

### Customer Insights

![Customer Insights](screenshots/customer-insights.png)

---

## How to Use

1. Clone or download this repository.
2. Open `dashboard/Mobile_Reviews_PowerBI_Dashboard.pbix` using Microsoft Power BI Desktop.
3. If Power BI asks for the dataset location, select `data/Mobile_Reviews_Sentiment.csv`.
4. Refresh the report.
5. Use the filters and slicers to explore the dashboard.

---

## Project Objective

The purpose of this project is to analyze customer review data and answer several business questions:

- Which brands and models receive better customer ratings?
- How does customer sentiment differ across products?
- Is there any relationship between product price and customer rating?
- Which product features receive stronger or weaker feedback?
- How does customer sentiment vary across countries?
- Are verified purchase reviews different from non-verified reviews?
- Which review platforms contribute the most review volume?

---

## Future Improvements

Possible improvements for this project include:

- Keyword analysis from review text
- Drill-through pages for individual brands and models
- Custom tooltip pages
- Year-over-year comparisons
- Power BI Service publishing
- Automated data refresh

---

## Author

Shiu Li Jie

Bachelor of Information Technology (Hons.)  
Business Intelligence and Analytics
