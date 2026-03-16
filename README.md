# Google Play Store Apps: Market & Insights Analysis

## Project Overview

Mobile app performance and user engagement are critical factors in today’s digital ecosystem.
This project analyzes **9,367 apps from the Google Play Store dataset** to understand market trends, user behavior, and monetization strategies.

Using **Google Looker Studio**, this analysis transforms raw app data into an **interactive dashboard and actionable insights** for developers, product managers, and marketing teams.

The goal is to identify **what makes an app successful** in terms of installs, ratings, reviews, and category performance.

---

# Business Problem

The Google Play Store contains thousands of applications competing for user attention.
Understanding market dynamics can help companies make **better product and marketing decisions**.

This project answers the following business questions:

* **Market Composition:** Which app categories dominate the ecosystem?
* **Pricing Strategy:** How do free vs paid apps perform?
* **User Sentiment:** What role do ratings and reviews play in app success?
* **Top Performers:** Which apps and categories lead in installs and engagement?

---

# Dataset

Dataset Source:
https://www.kaggle.com/datasets/lava18/google-play-store-apps

Dataset contains **9,367 applications** and includes the following attributes:

* **App:** Name of the application
* **Category:** App category (Game, Tools, Finance, etc.)
* **Rating:** Average user rating
* **Reviews:** Number of user reviews
* **Size:** App size
* **Installs:** Number of installs
* **Type:** Free or Paid
* **Price:** Price of the app
* **Content Rating:** Target age group
* **Genres:** App genre
* **Last Updated:** Last update date

---

# Methodology & Tools

## Tools Used

* **Google Looker Studio** – Dashboard creation
* **Excel / SQL** – Data cleaning and preprocessing
* **Data Visualization** – Charts, KPI cards, tables

## Analytical Approach

1. **Data Cleaning**

   * Removed duplicates
   * Converted installs and price into numeric format
   * Handled missing values

2. **Exploratory Data Analysis (EDA)**

   * Category distribution
   * Free vs Paid apps comparison
   * Ratings distribution

3. **Correlation Analysis**

   * Relationship between installs, ratings, and reviews

4. **Dashboard Development**

   * Interactive visualizations for business insights

---

# Dashboard Preview

![Dashboard](Dashboard.png)

The dashboard includes:

* KPI cards (Total Apps, Installs, Reviews, Average Rating)
* Category-wise app distribution
* Installs by category
* Rating distribution
* Free vs Paid apps comparison
* Top performing apps table

---

# Key Insights

### Market Overview

* **Total Apps:** 9,367
* **Average Rating:** 4.19
* **Total Installs:** 167+ Billion
* **Total Reviews:** ~6K

### Free vs Paid Apps

* **92.6% apps are Free**
* Only **7.4% apps are Paid**

Free apps dominate the market due to higher accessibility and adoption.

### Top Installed Apps

| App              | Installs    |
| ---------------- | ----------- |
| Subway Surfers   | 6 Billion   |
| Candy Crush Saga | 3 Billion   |
| 8 Ball Pool      | 600 Million |

### Category Insights

High performing categories:

* **Games**
* **Communication**
* **Productivity**
* **Social**
* **Family**

Games lead the market in installs and engagement.

### User Sentiment

* Average rating **4.19 / 5**
* Apps with higher ratings tend to receive more installs.

---

# Business Recommendations

### For Developers

* Focus on **free apps with monetization strategies**
* Improve **UX and performance** to maintain ratings above 4.0

### For Marketing Teams

* Promote apps in **high-demand categories**
* Encourage **user reviews and ratings**

### For Product Teams

* Maintain **regular updates**
* Monitor user feedback for feature improvements

### For Business Strategy

* Explore **niche markets** like:

  * Medical
  * Finance
  * Lifestyle

These categories have **lower competition but growing demand**.

---

# Project Structure

```
Google-Play-Store-Insights
│
├── Dashboard.png
├── googleplaystore.csv
├── EDA_Report.pdf
├── App_Insights_Dashboard.pdf
└── README.md
```

---

# Future Improvements

* Machine Learning model to **predict app success**
* Sentiment analysis on user reviews
* Time-series analysis for install trends
* Advanced category performance analysis

---

# Author

**Adarsh Dwivedi**
Data Analytics Project

---

# Conclusion

This project demonstrates how **data analytics and visualization** can uncover valuable insights from mobile app datasets.

By analyzing installs, ratings, reviews, and categories, businesses can make **data-driven decisions to improve app success in the competitive mobile market.**
