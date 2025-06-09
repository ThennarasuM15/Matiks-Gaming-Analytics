# 📊 Matiks Gaming Analytics Dashboard

> **A full-cycle product analytics case study** built using real-world simulated data for a gamified math platform **"MATIKS"**.

---

## 🧱 Project Summary

This project explores user behavior, retention, churn risk, and monetization patterns for **Matiks**, a gaming platform focused on interactive math learning.  
The solution integrates **Python** for data cleaning and transformation, and **Power BI** for dashboarding, storytelling, and executive-ready insights.

---

## 🧠 Tools & Stack

- **Power BI** — Dashboarding, KPIs, custom visuals  
- **Python (Pandas)** — Data wrangling, segmentation logic  
- **DAX** — Custom metrics, filters, and logic  
- **Excel** — Quick reference during cleanup

---

## 🧪 Key Data Processes

- ✅ Cleaned and validated 10,000 user records  
- ✅ Flagged **Username–Email duplication** issues for data quality awareness  
- ✅ Categorized **206 users as `"Invalid"`** due to negative retention (e.g., `Signup_Date > Last_Login`) — *not removed*, but **excluded from retention-based logic**  
- ✅ Created **Retention Days Segments** (1⭐–5⭐) using retention days range of thresholds  
- ✅ Derived **Churn Category** (`Active`, `At Risk`, `Likely Churned`) based on `Days_Since_Last_Login`  
- ✅ Binned Age Groups and Revenue Segments for cleaner visualization and behavioral analysis

---

## 📊 Dashboard Structure

### 🔹 **Page 1: User Engagement Overview**

- KPIs: Unique Users, DAU/WAU/MAU (window-based logic), Avg. Retention  
- Segment Visuals: Retention Stars, Churn Status, Age, Gender, Device Type  
- Filters: Referral Source, Game Mode  
- 📌 Includes summary notes and info tooltips per visual

---

### 🔹 **Page 2: Customer Behavior Analysis**

- Heatmap: Retention Segment × Churn Category  
- Scatter: Avg. Retention vs Total Revenue (by churn segment)  
- Table: At-Risk High-Value Users (Top Revenue, High Login Gaps)  
- Stacked Bar: Game Mode vs Retention Tier  
- 🎯 Focused on reactivation, dropoff zones, and gameplay preference

---

### 🔹 **Page 3: Revenue Insights**

- KPIs: Total Revenue, Revenue/User, Revenue/Session  
- Breakdown by: Retention Tier, Subscription Tier, Device, Churn Category  
- Top 10% segment revenue contribution (Power Users)  
- Segmentation Table: Revenue + Retention + Churn cross-view

---

## 📌 Special Notes

- 🛠️ **206 invalid records** (e.g., negative retention) were not deleted — instead, tagged as `"Invalid"` and excluded from engagement logic  
- 📧 **Username & Email duplication** was identified and flagged — retained for potential fraud or duplicate account detection  
- 🔁 DAU/WAU/MAU simulated using inferred activity windows (from `Signup_Date` to `Last_Login`) due to absence of raw login logs

---

## 💡 Key Insights

- ⭐ 4–5 Star users = **40%+ of total users** — highly engaged  
- 💔 Likely churned users contribute **over 50% of total revenue** — high reactivation potential  
- 🎮 Multiplayer & Co-op game modes = strongest engagement  
- 💰 Top 10% of users = ~60% of revenue — focus for retention and reward systems

---

## Source Data Credits 

- **MATIKS a math based gaming platform**


