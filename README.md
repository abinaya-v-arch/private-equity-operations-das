# Private Equity Operations Performance Dashboard

An operational analytics dashboard tracking document processing throughput, Quality Check (QC) accuracy, and Service Level Agreement (SLA) compliance across private equity middle-office operations.

---

## 📌 Project Overview

![Private Equity Operations Dashboard](screenshots/executive_summary.png)

Alternative investment operations require strict oversight when handling partner notices, quarterly capital accounts, and subscription packs:
* Monitoring document intake across portals (**Investran**, **eFront**, **Allvue**, **FIS Investier**).
* Tracking analyst turnaround times against contractual SLA benchmarks.
* Pinpointing root causes of QA errors (metadata mismatches, missing signatures).

---

## 🛠️ Tools Used
* **Microsoft Excel:** Raw transaction synthesis and data validation.
* **Power BI Desktop:** Operational data modeling and DAX KPI calculations.
* **Power Query:** Extraction, cleaning, and status columns.
* **Design Colors:** Navy Blue (`#0B2545`), Gold (`#D4AF37`), White (`#FFFFFF`).

---

## 📊 Key Operational Metrics (DAX)
* **Total Volume:** `500` documents processed across 2024.
* **Completed Yield:** `429` documents transitioned to Completed status.
* **Operational Accuracy Rate (%):** `85.8%` first-time-right quality check pass rate.
* **Mean Turnaround Time:** `~37` minutes average processing time.
* **SLA Adherence (%):** `83.6%` completed within target turnaround windows.

---

## 📁 Repository Structure
* `data/document_operations.csv` - Operational dataset (500 records).
* `documentation/project_case_study.md` - Business context and problem statement.
* `documentation/power_bi_build_guide.md` - Step-by-step DAX formulas and dashboard setup.
* `screenshots/` - Dashboard preview images.

---

## 👤 Author
* **Profile:** M.Com Graduate | Ex-MSCI Private Equity Operations
* **GitHub:** [@abinaya-v-arch](https://github.com/abinaya-v-arch)
