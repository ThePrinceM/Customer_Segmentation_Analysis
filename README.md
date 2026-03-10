# Customer_Segmentation_Analysis
Audience Segmentation Analysis using website analytics data to classify users based on geographic location, device type, and behavioral patterns. The project performs exploratory data analysis, visualization, and clustering to identify different audience segments and understand user engagement.

# Audience Segmentation Analysis

## Project Overview

This project performs **Audience Segmentation Analysis** using website analytics data. The goal is to classify website visitors into different groups based on **geographic location, device type, and user behavior**.

By analyzing visitor interaction patterns, this project helps identify how different audience segments engage with a website.

The project includes **data preprocessing, exploratory data analysis (EDA), visualization, and clustering techniques** to understand user demographics and behavior.

---

## Objectives

The main objectives of this project are:

* Analyze website visitor data.
* Segment users based on **device type (mobile, desktop, tablet)**.
* Study visitor distribution across **different countries**.
* Analyze **user engagement metrics** such as page views and session duration.
* Identify **behavior-based audience segments** using clustering techniques.
* Generate insights that can help improve **website performance and marketing strategies**.

---

## Dataset

The dataset used in this project comes from the **Google Analytics Customer Revenue Prediction dataset** available on Kaggle.

The dataset contains **session-level website analytics data**, including information about visitors, device types, traffic sources, and engagement metrics.

### Key Features Used

| Feature    | Description                               |
| ---------- | ----------------------------------------- |
| country    | Visitor's geographic location             |
| device     | Device category (mobile, desktop, tablet) |
| pageviews  | Number of pages visited during a session  |
| bounces    | Indicator of single-page sessions         |
| timeOnSite | Time spent on the website                 |

---

## Technologies Used

* **Python**
* **Pandas** – Data manipulation and preprocessing
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning (K-Means clustering)
* **Jupyter Notebook** – Development environment

---

## Project Workflow

The project follows the following data science workflow:

1. **Data Collection**

   * Download dataset from Kaggle.

2. **Data Preprocessing**

   * Extract JSON fields.
   * Select relevant features.
   * Handle missing values.

3. **Exploratory Data Analysis (EDA)**

   * Analyze visitor distribution by device.
   * Identify top countries contributing to traffic.
   * Study user engagement metrics.

4. **Data Visualization**

   * Device distribution charts
   * Country-wise visitor analysis
   * Engagement heatmaps
   * Device vs behavior analysis

5. **Audience Segmentation**

   * Apply **K-Means clustering** to group users based on behavior.

6. **Insights and Interpretation**

   * Identify high-engagement users
   * Understand device-based behavior
   * Analyze geographic traffic patterns

---

## Visualizations

The project includes the following visualizations:

* Visitor Distribution by Device
* Top Countries by Website Traffic
* Device vs Engagement Heatmap
* Device vs Country Usage Chart
* Audience Behavior Segmentation Scatter Plot

These visualizations help in understanding **how different audience segments interact with the website**.

---

## Key Insights

Some important insights from the analysis include:

* **Mobile devices generate the majority of website traffic.**
* **Desktop users tend to have higher engagement levels.**
* Certain countries contribute significantly to website visits.
* Users can be segmented into **low, medium, and highly engaged audiences** based on behavior metrics.

---

## Business Implications

The insights obtained from audience segmentation can help organizations:

* Improve **mobile website optimization**.
* Target marketing campaigns toward **high-engagement regions**.
* Personalize content for different audience segments.
* Reduce bounce rates and improve **user engagement**.

---

## Project Structure

```
Audience-Segmentation-Analysis
│
├── dataset
│   └── train_v2.csv
│
├── notebook
│   └── audience_segmentation_analysis.ipynb
│
├── visuals
│   └── charts
│
└── README.md
```

---

## Future Improvements

Possible improvements for this project include:

* Building an **interactive dashboard** using Power BI or Tableau.
* Using **advanced clustering techniques** for better segmentation.
* Performing **predictive modeling** to forecast user engagement.

---

## Author

Developed as part of a **Data Analytics / Data Science project** to demonstrate audience segmentation and user behavior analysis using website analytics data.

---
