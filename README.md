<div align="center">

<!-- ANIMATED BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=☕%20Coffee%20Sales%20Dashboard&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=36&desc=Power%20BI%20%7C%20Sales%20Analytics%20%7C%20Business%20Intelligence&descAlignY=58&descSize=18" width="100%"/>

<br/>

<!-- BADGES -->
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/Data%20Analytics-FF6F00?style=for-the-badge&logo=databricks&logoColor=white" />
<img src="https://img.shields.io/badge/Business%20Intelligence-00B4D8?style=for-the-badge&logo=tableau&logoColor=white" />
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />

<br/><br/>

<img src="https://img.shields.io/github/stars/yourusername/coffee-sales-dashboard?style=social" />
<img src="https://img.shields.io/github/forks/yourusername/coffee-sales-dashboard?style=social" />
<img src="https://img.shields.io/github/watchers/yourusername/coffee-sales-dashboard?style=social" />

</div>

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🗂️ Table of Contents

<div align="center">

| Section | Description |
|:-------:|:------------|
| [☕ Overview](#-project-overview) | What this project solves |
| [🔧 Tools Used](#-tools--technologies) | Tech stack & skills |
| [📊 Key Results](#-key-results) | Business impact metrics |
| [🧠 Technical Skills](#-technical-skills-demonstrated) | DAX, Data Model, UX |
| [💼 Business Impact](#-business-impact) | Real-world value |
| [🚀 How to Use](#-how-to-use) | Setup guide |
| [📸 Dashboard Preview](#-dashboard-preview) | Screenshots |

</div>

---

## ☕ Project Overview

<img align="right" src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="120" />

> **A fully interactive Power BI dashboard that transforms raw coffee sales transaction data into actionable business intelligence — helping coffee shop owners understand revenue patterns, peak demand periods, and customer spending behaviour across weekdays and weekends.**

### 🎯 Problem Solved

Coffee shop managers often struggle with:

- ❓ **Not knowing peak hours** — resulting in understaffing during rush hours and overstaffing during slow periods
- ❓ **No visibility into weekday vs weekend revenue splits** — making it impossible to plan promotions effectively
- ❓ **Manual spreadsheet analysis** — slow, error-prone, and not real-time
- ❓ **No product-level sales insight** — not knowing which coffee products drive the most revenue

This dashboard solves all of the above with **real-time slicers, KPI cards, trend charts, and time-of-day breakdowns** — all in a single interactive view.

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🔧 Tools & Technologies

<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║              TECHNOLOGY STACK                                  ║
╠══════════════════╦════════════════════════════════════════════╣
║  Visualization   ║  Microsoft Power BI Desktop                ║
║  Query Language  ║  DAX (Data Analysis Expressions)           ║
║  Data Modeling   ║  Star Schema / Relationship Model          ║
║  Data Source     ║  Coffee Sales Transaction Data             ║
║  Design          ║  Custom Themes, Background, Animated GIFs  ║
║  Interactivity   ║  Slicers, Drill-through, Navigation Btns   ║
╚══════════════════╩════════════════════════════════════════════╝
```

</div>

<br/>

<div align="center">

| Category | Tools |
|:--------:|:------|
| 📊 **BI Platform** | Microsoft Power BI Desktop 2025 |
| 🧮 **DAX Measures** | Custom KPI measures, Time intelligence, Aggregations |
| 🗃️ **Data Model** | `coffee_data` table with Date hierarchy, Weekday dimension |
| 🎨 **Design** | Custom background image, animated coffee GIF, action buttons |
| 📐 **Visuals Used** | Card KPIs, Line Chart, Column Chart, Donut Chart, Slicer |
| 🔗 **Navigation** | Multi-page report with interactive button navigation |

</div>

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 Key Results

<div align="center">

<!-- ANIMATED STATS ROW -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6&height=3&section=header" width="100%"/>

</div>

<br/>

### 📌 KPI Cards Built (9 Measures)

<div align="center">

| # | KPI Metric | DAX Measure | Insight Provided |
|:-:|:-----------|:------------|:-----------------|
| 1 | ☕ **Total Revenue** | `Total_Revenue` | Overall sales performance |
| 2 | 🥤 **Total Cups Sold** | `Total_Cups_Sold` | Volume of transactions |
| 3 | ⏰ **Peak Hour Sales** | `Peak_Hour_Sales` | Revenue during busiest hour |
| 4 | ☕ **Peak Hour Cups** | `Peak_Hour_Cups` | Units sold at peak time |
| 5 | 🏷️ **Peak Hour Label** | `Peak_Hour_Label` | Dynamic hour text label |
| 6 | 📅 **Weekday Spends** | `Weekday_Spends` | Mon–Fri total revenue |
| 7 | 🎉 **Weekend Spends** | `Weekend_Spends` | Sat–Sun total revenue |
| 8 | 📈 **Avg Weekday Spend** | `Avg_Weekday_Spends` | Daily average Mon–Fri |
| 9 | 📈 **Avg Weekend Spend %** | `Avg_Weekend_Spends_%` | Weekend vs total ratio |

</div>

<br/>

### 📈 Charts & Visualizations

```
📉 LINE CHART     →  Revenue trend over Time (Year → Quarter → Month drill-down)
📊 COLUMN CHART   →  Sales by Day of Week  (Mon, Tue, Wed ... Sun)
🍩 DONUT CHART    →  Transactions by Time of Day (Morning / Afternoon / Evening / Night)
🔍 SLICER         →  Filter by Coffee Product Name
🔘 ACTION BUTTONS →  Page-to-page navigation with custom design
```

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🧠 Technical Skills Demonstrated

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,vscode" />

</div>

<br/>

### 💡 DAX Development

```dax
-- Example: Peak Hour Detection using DAX
Peak_Hour_Sales = 
    CALCULATE(
        SUM(coffee_data[Price]),
        FILTER(
            coffee_data,
            coffee_data[Hour] = [Peak_Hour_Value]
        )
    )

-- Weekday vs Weekend Split
Weekday_Spends = 
    CALCULATE(
        SUM(coffee_data[Price]),
        WEEKDAY(coffee_data[Date], 2) <= 5
    )

-- Average Weekend Spend Percentage
Avg_Weekend_Spends_% = 
    DIVIDE([Weekend_Spends], [Total_Revenue], 0)
```

<br/>

### 📐 Data Modeling Skills

- ✅ Built **Date Hierarchy** (Year → Quarter → Month) for time-intelligence analysis
- ✅ Created **`Weekday` dimension** from date column for day-of-week analysis
- ✅ Designed **`Time_of_Day`** categorical field (Morning / Afternoon / Evening / Night)
- ✅ Implemented **9 custom DAX measures** in a dedicated `Measure_` table
- ✅ Optimised data model for fast slicer performance

<br/>

### 🎨 Report Design Skills

- ✅ Custom **coffee-themed background** image (PNG)
- ✅ Embedded **animated coffee GIF** for visual appeal
- ✅ Designed **9 KPI card visuals** with clear labeling
- ✅ Multi-page navigation using **action buttons**
- ✅ Applied **Power BI CY25 theme** for consistent styling

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 💼 Business Impact

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                    BUSINESS VALUE                            │
├──────────────────────┬──────────────────────────────────────┤
│  👥 Staffing          │  Know exact peak hours → right-size  │
│                      │  staff rosters, reduce labour cost    │
├──────────────────────┼──────────────────────────────────────┤
│  📣 Marketing         │  Weekend vs weekday spend data →     │
│                      │  launch targeted weekend promotions   │
├──────────────────────┼──────────────────────────────────────┤
│  ☕ Product Mix       │  Coffee name slicer → identify top   │
│                      │  sellers, discontinue slow movers     │
├──────────────────────┼──────────────────────────────────────┤
│  📅 Operations        │  Day-of-week chart → plan inventory  │
│                      │  and prep based on busiest days       │
├──────────────────────┼──────────────────────────────────────┤
│  💰 Revenue Growth    │  Trend line analysis → identify      │
│                      │  growth months and seasonal dips      │
└──────────────────────┴──────────────────────────────────────┘
```

</div>

<br/>

### 🏆 Value Delivered

- 🚀 Replaced **manual Excel reporting** with real-time interactive dashboard
- 📉 Reduced time-to-insight from **hours to seconds**
- 🎯 Enabled **data-driven decisions** on staffing, promotions, and product mix
- 🔄 Built **reusable report structure** scalable across multiple store locations

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📸 Dashboard Preview

<div align="center">

> 📌 *Replace the placeholders below with actual screenshots from Power BI*

| Page 1 — Main Dashboard | Page 2 — Navigation Hub |
|:-----------------------:|:-----------------------:|
| ![Dashboard Page 1](screenshots/page1.png) | ![Dashboard Page 2](screenshots/page2.png) |
| 9 KPI Cards + 3 Charts + Slicer | Navigation Button Panel |

</div>

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🚀 How to Use

### Prerequisites

```bash
✅ Microsoft Power BI Desktop (Free — download from Microsoft Store)
✅ Windows OS (Power BI Desktop is Windows-only)
```

### Steps

```
1️⃣  Clone this repository
    git clone https://github.com/yourusername/coffee-sales-dashboard.git

2️⃣  Open Power BI Desktop

3️⃣  File → Open → Select Coffee_sales.pbix

4️⃣  Interact with the dashboard:
     • Use the coffee name SLICER to filter by product
     • Click the LINE CHART to drill from Year → Quarter → Month
     • Use NAVIGATION BUTTONS to switch between pages
     • Hover over charts for detailed tooltips
```

---

<!-- ANIMATED DIVIDER -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📁 Project Structure

```
📦 coffee-sales-dashboard
 ┣ 📊 Coffee_sales.pbix          ← Main Power BI report file
 ┣ 📁 screenshots/
 ┃ ┣ 🖼️ page1.png                ← Dashboard page 1 screenshot
 ┃ ┗ 🖼️ page2.png                ← Navigation page screenshot
 ┣ 📄 README.md                  ← This file
 ┗ 📄 LICENSE
```

---

## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://yourportfolio.com)

</div>

---

<!-- FOOTER WAVE -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&fontSize=20&fontColor=fff&animation=twinkling" width="100%"/>

<div align="center">

</div>
