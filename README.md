<div align="center">

# 📊 EPC Weekly Report Dashboard

**A fully interactive weekly reporting dashboard for a high-voltage overhead transmission line EPC project**

*Built with Power BI · Covers Engineering, Procurement, Site Works & Progress tracking*

![Data Date](https://img.shields.io/badge/Data%20Date-19--Mar--2026-4B5563?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Progress-F59E0B?style=for-the-badge)
![Type](https://img.shields.io/badge/Contract-EPC-6366F1?style=for-the-badge)

</div>

---

## 📌 Project Overview

This repository contains the **weekly reporting dashboard** developed for a high-voltage overhead transmission line EPC project. The dashboard consolidates multi-source project data — schedule, procurement, cost, and site works — into a single interactive report delivered to senior management every week.

| Field | Details |
|---|---|
| **Project Type** | EPC — High-Voltage Overhead Transmission Line |
| **Client** | SEC (Saudi Electricity Company) |
| **Data Date** | 19 March 2026 |
| **Project Timeline** | Aug 2025 → Sep 2027 |
| **Planned TCC** | 17 Feb 2027 |
| **Expected TCC** | 25 Apr 2027 |
| **Planned FAC** | 17 Jul 2027 |
| **Expected FAC** | 16 Sep 2027 |
| **Developed by** | Karim Hossam |

---

## 📂 Dashboard Pages

The dashboard is built as a **multi-page interactive report** with a sidebar navigation. Each page is a self-contained data view:

| Page | What it shows |
|---|---|
| **Home** | Project identity card — name, contract number, data date |
| **Milestones** | KPI cards for 3 contractual dates + overall S-curve chart |
| **Engineering** | Planned % vs. actual %, variance, activity-level progress table |
| **Procurement** | Procurement cycle stage tracking + item-level progress bar chart |
| **Site Works** | Trade-level schedule % vs. progress % with variance |
| **Progress** | S-curves, work-in-progress table, 4-week lookahead, photos, AOC log |

---

## ⚙️ Technical Implementation

### Data model
- Unified data model aggregating schedule exports, procurement logs, and cost data into a single source of truth
- Relationships built between activity IDs, procurement items, and cost line items

### KPI calculations
- **Planned %** — time-weighted progress derived from baseline schedule
- **Actual %** — reported progress mapped against activity completion
- **Variance** — deviation in calendar days between planned and expected finish
- **SPI (Schedule Performance Index)** — actual % / planned % per activity
- **Total Float** — slack days before an activity hits the critical path

### Visualizations built
- Dynamic **S-curves** — cumulative & monthly planned / actual / remaining (dual Y-axis)
- **Progress bar charts** — grouped planned vs. actual per workstream
- **Activity status donut/bar charts** — Completed / In Progress / Not Started breakdown
- **Procurement cycle tracker** — stage-by-stage status across multiple items
- **Work-in-progress table** — filterable by discipline with conditional formatting on float & variance
- **4-week lookahead table** — forward schedule sorted by planned start
- **AOC log table** — risk register with type, impact, action, and owner columns

---

## 🛠️ Tools & Skills

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

| Skill | Application |
|---|---|
| Dashboard Development | Multi-page interactive report with navigation |
| Variance & SPI Analysis | Schedule performance tracking per discipline |
| S-Curve Modelling | Planned vs. actual vs. remaining cost & progress |
| Data Aggregation | Unified model from schedule, procurement & cost sources |
| KPI Reporting | Milestone tracking, activity status, procurement cycle |
| Risk Reporting | AOC documentation with impact & corrective actions |

---

## 🖼️ Screenshots

### Home
![Home](./Example_page-0001.jpg)

### Milestones
![Milestones](./Example_page-0002.jpg)

### Engineering
![Engineering](./Example_page-0003.jpg)

### Procurement
![Procurement](./Example_page-0004.jpg)

### Site Works
![Site Works](./Example_page-0005.jpg)

### Progress — S-Curves
![S-Curves](./Example_page-0006.jpg)

### Progress — Work in Progress
![Work in Progress](./Example_page-0007.jpg)

### Progress — Lookahead
![Lookahead](./Example_page-0008.jpg)

### Progress — Photos
![Photos](./Example_page-0009.jpg)

### Progress — AOC
![AOC](./Example_page-0010.jpg)

---

## 📁 Repository Structure

```
📦 epc-weekly-report
 ┣ 📄 README.md                # This file
 ┣ 📁 screenshots/             # Dashboard page screenshots
 ┣ 📁 data/
 ┃ ┣ 📄 schedule_export.xlsx   # Schedule data export
 ┃ ┣ 📄 procurement_log.xlsx   # Procurement cycle tracker
 ┃ ┗ 📄 cost_data.xlsx         # Monthly cost actuals
 ┗ 📁 exports/
   ┗ 📄 Example.pdf            # Sample weekly report export
```

---

## 👤 Developer

**Karim Hossam** — Full Stack Engineer & Data Analyst

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://karim-hossam.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/karim-h-14a36b320)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:karim.hossam.essa@gmail.com)
