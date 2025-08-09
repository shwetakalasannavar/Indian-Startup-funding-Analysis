# Indian-Startup-funding-Analysis


## 📌 Overview

This project analyzes a **Startup Funding** dataset to uncover trends, top-performing sectors, cities, startups, and active investors.
The script processes raw data, cleans it, and generates insightful visualizations to help investors and startup founders make informed decisions.

---

## 🛠 Features

* **Data Cleaning & Preprocessing**

  * Standardizes column names
  * Handles missing values
  * Converts funding amounts to numeric values
  * Parses dates for time-series analysis

* **Trend Analysis**

  * Funding trends over time
  * Top sectors, cities, startups, and investors
  * Investment type distribution

* **Visualizations**

  * Line charts for trends
  * Bar plots for categorical insights

* **Recommendations**

  * Suggests strategies for investors and startup founders

---

## 📂 Project Structure

```
main.py                # Main analysis script
startup_funding.csv    # Dataset file (not included in repo)
README.md              # Documentation
```

---

## 📦 Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas matplotlib seaborn
```

---

## ▶️ How to Run

1. Place your dataset file (`startup_funding.csv`) in the specified location (e.g., `/content/startup_funding.csv`).
2. Run the script:

```bash
python main.py
```

---

## 📊 Output

* **Funding Trends Over Time** – Line chart showing total funding per month
* **Top 10 Sectors** – Bar chart of sectors with the highest funding count
* **Top 10 Cities** – Bar chart of cities with the most startup funding
* **Top 10 Startups** – Bar chart of startups with most funding rounds
* **Top 10 Active Investors** – Bar chart of investors with the most deals
* **Investment Type Distribution** – Count plot showing investment type frequency

---

## 📌 Notes

* The dataset path in `main.py` is currently hardcoded as `/content/startup_funding.csv`. Update it if needed.
* Make sure your dataset contains at least the following columns:

  * `Date`
  * `Startup Name`
  * `Industry Vertical`
  * `City/Location`
  * `Investors Name`
  * `Investment Type`
  * `Amount in USD`

---

## 💡 Example Recommendations Output

```
Recommendations for Investors and Startup Founders:
1. Focus on top-performing sectors like Technology, which attract the most funding.
2. Cities like Bengaluru are hotspots for startups.
3. Investment types like Seed Funding dominate, consider aligning strategies accordingly.
4. Investors should monitor funding trends and target periods of high activity.
```

---

