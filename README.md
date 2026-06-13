# Snapdeal Product Analytics Dashboard (Power BI)

## Project Overview

This project analyzes Snapdeal product data using Power BI to uncover insights related to pricing strategy, customer satisfaction, promotional effectiveness, product risk, customer trust, and dynamic price segmentation.

The dashboard was developed as part of an analytics internship assignment and focuses on solving six business problems using DAX, measures, KPIs, and interactive visualizations.

---

## Dataset

The dataset contains Snapdeal product information including:

* Product Name
* Category
* Brand
* Price
* Discount
* Rating
* Reviews Count
* Scraping Date
* Other product-related attributes

Several required business metrics such as Sales, Return Rate, Inventory Value, and historical promotional data were unavailable. Appropriate proxy measures were created using available fields and documented within the analysis.

---

## Tools Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling
* Interactive Dashboards
* KPI Cards
* Scatter Charts
* Clustered Column Charts
* Tables and Filters

---

# Task 1: Pricing vs Satisfaction Exception Detection

### Objective

Identify products that are overpriced, poorly rated, high risk, and underperforming.

### Key Features

* Category Average Price Analysis
* Category Average Rating Analysis
* Risk Score Identification
* Critical Failure Product Detection

### Screenshots

![Task 1](Task%201.png)

![Task 1.1](Task%201.1.png)

---

# Task 2: Promotion Effectiveness Trend Analysis

### Objective

Evaluate promotional discount behavior and estimate promotional lift using available discount information.

### Key Features

* Average Discount Analysis
* Baseline Discount Estimation
* Promotional Lift Calculation
* Promotion Effectiveness Comparison

### Screenshot

![Task 2](Task%202.png)

---

# Task 3: Discount vs Rating Causation Analysis

### Objective

Analyze whether higher discounts improve customer satisfaction or simply increase customer engagement.

### Key Features

* Discount vs Rating Scatter Analysis
* Review Volume Segmentation
* Customer Engagement Proxy Analysis

### Screenshot

![Task 3](Task%203.png)

---

# Task 4: Financially Risky Inventory KPI

### Objective

Identify products creating financial risk due to high discounts, low ratings, and customer exposure.

### Key Features

* Custom Risk Score
* Financial Risk KPI
* Conditional Formatting
* Risk Classification

### Screenshot



---

# Task 5: Trust-Weighted Rating Index

### Objective

Compare customer satisfaction using multiple rating methodologies.

### Key Features

* Simple Average Rating
* Review-Weighted Rating
* Trust-Weighted Rating
* Trust Score Analysis

### Screenshots

![Task 5](Task%205.png)

![Task 5.1](Task%205.1.png)

---

# Task 6: Context-Aware Price Banding

### Objective

Create dynamic percentile-based price bands that automatically respond to filter context.

### Key Features

* Dynamic 30th Percentile Threshold
* Dynamic 70th Percentile Threshold
* Low, Medium, High Price Classification
* Filter-Aware Pricing Analysis

### Screenshots

![Task 6](Task%206.png)

---

## Assumptions

Several required business metrics were not available in the dataset. Therefore:

* Reviews Count was used as a proxy for customer engagement and sales activity.
* Custom risk metrics were derived using available fields.
* Return Rate was replaced with a trust-confidence factor based on review volume.
* Historical promotional analysis was approximated using current snapshot data.
* Dynamic percentile calculations were implemented using DAX measures and filter context.

---

## Key Business Insights

* High discounts do not necessarily improve customer satisfaction.
* Some products are overpriced relative to their category performance.
* Customer trust depends on both ratings and review volume.
* A significant portion of customer engagement is concentrated in risky products.
* Dynamic price segmentation provides more meaningful insights than static price bands.
* Context-aware pricing analysis improves decision-making across categories and brands.

---

## Author

**Ishika**

Power BI Analytics Project

