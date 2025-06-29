# IPL_Analysis
Sure! Here's your GitHub-friendly version of the **IPL Analysis** project details, formatted for a `README.md` file:

---

# IPL Analysis

## 📊 Project Overview

This project analyzes real-time IPL match data from **2008 to 2017**, sourced from Kaggle. The goal is to identify performance trends, player impact, and match outcomes across seasons. Data was explored in Excel, cleaned using **PostgreSQL**, and visualized using **Power BI** to create interactive dashboards with KPIs and filters.

---

## 🛠️ Tools & Technologies

* **Excel** – Initial data review and exploration
* **PostgreSQL** – Data cleaning, transformation, and flag creation
* **Power BI** – Data visualization and dashboard building

---

## 🧹 Data Cleaning Process

Data cleaning was done using **PostgreSQL**, where:

* Null and inconsistent values were handled
* Several useful flags were created for analysis:

  * `dls` – Indicates if DLS (Duckworth–Lewis) method was applied
  * `match_resulted` – Identifies if the match produced a valid result
  * `is_win_by_runs` – Flags matches won by defending the score
  * `is_win_by_wickets` – Flags matches won by chasing
  * `toss_win_match_win` – Checks if toss winner also won the match

---

## 📈 Data Visualization

Interactive dashboards were built in **Power BI** with filters for:

* Season-wise match trends
* Toss impact and decision patterns
* Team-wise and venue-based performance
* Top players of each season
* DLS impact and home advantage insights

---

## 🔍 Key Insights

* Toss decisions influenced outcomes, especially in key venues
* Some teams had consistent season-wise dominance
* Certain venues favored the toss-winning team
* Duckworth–Lewis method impacted result patterns
* Player-of-the-match awards revealed season MVPs

---
## Project Snapshot: Core Insights and Visualizations

![IPL_Analysis](https://github.com/user-attachments/assets/03c0de8c-2582-43ba-bcb1-5681207439d9)


