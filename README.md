# Quick Commerce Addiction: A Data Story on India's 10-Minute Delivery Habit

Three Power BI dashboards analyzing customer behavior on Zepto, Blinkit, and 6 other Indian quick commerce platforms (Swiggy Instamart, Big Basket, Flipkart Minutes, Amazon Now, Dunzo, Jio Mart), built to answer one question: is India's love for 10-minute delivery actually a habit, or does the data say something different?

Full write-up on Medium and the LinkedIn post.
---

## Why I built this

Quick commerce apps get talked about constantly, but mostly in vibes: "Gen Z is lazy", "it's all about speed", "people are addicted". I wanted to check what the numbers actually say instead of repeating the same assumptions everyone makes. This project is as much about storytelling with data as it is about the dashboards themselves.

## What's inside

| Dashboard | Focus |
|---|---|
| `Zepto_Dashboard.pbix` | Customer retention, delivery time vs distance, satisfaction sentiment, payment mode share, revenue by age group |
| `Blinkit_Dashboard.pbix` | Order timing by hour, campaign cost vs revenue ROI, category-level demand, delivery time by hour |
| `Quick_Commerce_Dashboard.pbix` | Cross-platform comparison across 8 major players — revenue, ratings, average order value, basket size, delivery distance and time, discount effect on baskets |


## Key findings

- **Revenue by age skews older, not younger.** On Zepto, the 45+ age group generates the highest revenue share, decreasing steadily down to 18-24. The "young impulsive shopper" narrative doesn't hold up in this dataset.
- **Weekday orders dominate weekend orders** (roughly 14.3K vs 5.7K on Zepto), suggesting quick commerce is used more as a routine restocking tool than an occasional treat.
- **Delivery speed doesn't clearly drive satisfaction.** Across the 8-platform comparison, Zepto leads on speed (9.6 min average) but that lead doesn't show up as a clear satisfaction advantage over slower platforms.
- **Referral programs outperform paid campaigns on ROI**, based on the Blinkit cost-vs-revenue view, ahead of channels like push notifications and category promotions.
- **Repeat customers make up ~60% of the base** on both Zepto (59.48%) and Blinkit (59.68%), and demand is concentrated in everyday essentials (dairy, household, groceries) rather than occasional-purchase categories, both signs of a habit-driven market rather than a discovery-phase one.

## Tools used

- Power BI (data modeling, DAX measures, dashboard design)
- Dataset: public dataset sourced from Kaggle — 
1) [Blinkit Sales Dataset](https://www.kaggle.com/datasets/akxiit/blinkit-sales-dataset)
2) [Zepto-Inspired Online Grocery & Delivery Dataset](https://www.kaggle.com/datasets/ashishjangir6494/zepto-inspired-online-grocery-and-delivery-dataset)
3) [Quick Commerce Dataset](https://www.kaggle.com/datasets/rohitgrewal/quick-commerce-dataset)

## Data note

This analysis is built on a publicly available dataset from Kaggle, not live or proprietary data from Zepto, Blinkit, or the other platforms named. I have used 3 kaggle datasets mentioned above. The insights reflect patterns in that dataset and are meant as a portfolio case study, not an official assessment of these companies.

## About me

I'm Sanskar, a B.Tech IT graduate looking for Data Analyst / Business Analyst / ML Engineer roles. This project is part of my portfolio to show dashboard design and data storytelling skills together, and not just charts on a page.

- GitHub: [github.com/SansKAr1909](https://www.github.com/SansKAr1909)
- LinkedIn: [linkedin.com/in/sanskar-ratandhara](https://www.linkedin.com/in/sanskar-ratandhara)
- Medium: [medium.com/@sanskar19](https://www.medium.com/@sanskar19)
