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

## 📂 Dashboard Sections

### 🏠 Home
Entry page showing project name, contract number, and data date.

---

### 🎯 Milestones
Tracks the three key contractual milestones against baseline:

| Milestone | Planned | Expected | Delay |
|---|---|---|---|
| TCC (Taking-Over Certificate) | 17-Feb-27 | 25-Apr-27 | +67 days |
| PAC (Provisional Acceptance) | 17-Apr-27 | 22-Jun-27 | +66 days |
| FAC (Final Acceptance) | 17-Jul-27 | 16-Sep-27 | +61 days |

Also includes overall S-curve with monthly planned vs. actual amounts (Aug 2025 – Sep 2027).

---

### ⚙️ Engineering

Tracks progress across Base Design and Detailed Design for the Electrical discipline.

| Metric | Value |
|---|---|
| Planned % | 24.46% |
| Actual % | 0.00% |
| Variance | **−53 days** |
| Expected Finish | 12 Apr 2027 |

**Activity breakdown:**

| Activity | Planned Finish | Expected Finish | Schedule % | Total Float |
|---|---|---|---|---|
| Base Design | 28-Jun-26 | 30-Jun-26 | 0.00% | +16 |
| Detailed Design | 04-Feb-27 | 12-Apr-27 | 1.10% | **−53** |

---

### 🚚 Procurement

Monitors the full procurement cycle (PO → Manufacture → ITP → FAT → FAT Report Approval) across 4 material categories.

| Metric | Value |
|---|---|
| Planned % | 1.70% |
| Actual % | **19.56%** ✅ ahead of plan |
| Variance | −50 days |
| Planned Finish | 26-Oct-26 |
| Expected Finish | 03-Jan-27 |

**Item-level progress (Schedule % / Progress %):**

| Item | Schedule % | Progress % |
|---|---|---|
| Stubs & Templates | 76.84% | 60.16% |
| Conductors | 55.95% | 0.00% |
| Hardware & Fittings | 0.00% | 0.00% |
| Steel Towers | 0.00% | 0.00% |

**FAT Status:**

| Status | Count |
|---|---|
| Completed | 3 |
| In Progress | 7 |
| Not Started | 21 |

---

### 🏗️ Site Works

| Metric | Value |
|---|---|
| Planned % | 2.83% |
| Actual % | 0.00% |
| Variance | **−54 days** |
| Expected Finish | 28 Mar 2027 |

| Trade | Schedule % | Progress % |
|---|---|---|
| Construction | 7.78% | 0.00% |
| Installation | 0.00% | 0.00% |

---

### 📈 Progress

Five sub-sections:

#### S-Curves
Cumulative and monthly cost tracking across all project phases:
- Project Preparation
- Engineering
- Equipment & Material
- Construction & Installation
- Testing & Commissioning
- Project Close Out

#### Work in Progress
Activity-level detail for all in-progress engineering tasks, including planned vs. actual start, expected finish, schedule %, progress %, and total float.

#### Lookahead (4-Week)
Forward-looking schedule covering General and Engineering (Electrical), showing upcoming planned activities and their expected finish dates.

#### Photos
Site progress photos (conductor reels, crane operations, tower erection works).

#### AOC — Areas of Concern

| Type | Issue | Impact | Action | Owner |
|---|---|---|---|---|
| External | SEC changed insulator type (Porcelain → Composite Silicone Rubber) | Increased hardware delivery lead time | Contract amendment | SEC |
| External | Route plan change | Delays engineering & construction | Contract amendment | SEC |
| Internal | Delay in latticed steel structure manufacturing | Delays tower erection | Expedite manufacturing | Procurement |

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

## 📁 Repository Structure

```
📦 epc-weekly-report
 ┣ 📄 README.md                # This file
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
