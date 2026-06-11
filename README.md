# Hospital Patient Flow & Bed Capacity Dashboard

## Overview
This repository features a Business Intelligence (BI) project focused on hospital operational efficiency. It analyzes the critical relationship between patient flow (admissions, transfers, discharges) and bed capacity utilization, highlighting bottlenecks and capacity constraints within a hospital setting.

## Project Assets

### 📊 Dashboard (PDF Export)
* **`Hospital_patient_flow_bed_capacity.pdf`:** A static export of the final operational dashboard (originally optimized for Looker Studio). This visualization provides an administrative view of current ward occupancies, patient movement metrics, and available bed capacity.

### 📁 Datasets (CSV)
* **`Patient_Flow_Data.csv`:** Contains transactional data regarding patient movement, including admission times, discharge times, and lengths of stay.
* **`Bed_Capacity_Data.csv`:** Contains structural data regarding the hospital's resources, including total beds per ward, occupied beds, and turnover rates.

## Potential Use Cases
Analyzing patient flow and bed capacity is essential for:
* **Reducing Wait Times:** Identifying bottlenecks in emergency departments (ED) waiting for inpatient beds.
* **Optimizing Staffing:** Aligning nursing staff schedules with peak admission or discharge hours.
* **Predictive Capacity:** Forecasting when wards will hit 100% capacity to enable proactive patient diversion.

## How to Use
1. **View the Dashboard:** Open the PDF file to explore the visualization layouts and KPI reporting structure.
2. **Rebuild the Dashboard:** Download the two CSV files and import them into Looker Studio, Tableau, or Power BI. Map the flow data against the capacity data to practice building joined operational reports.

> **Disclaimer:** All data within this repository is synthetic and created for educational portfolio demonstration purposes. It does not contain any real demographic or Protected Health Information (PHI).
