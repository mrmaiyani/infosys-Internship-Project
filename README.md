# MedTrack DV — Hospital Operations & Patient Analytics Dashboard

A hospital operations and patient analytics dashboard suite that turns raw hospital data into KPI-driven insights for administrators, healthcare managers, and policymakers.

## Overview

MedTrack DV transforms hospital and patient admission data into four interactive dashboards, helping teams monitor patient flow, evaluate department performance, optimize resources, and support data-driven decisions.

## Dashboards

- **Hospital Overview** — admissions, occupancy, and readmission trends
- **Patient Flow** — admission/discharge tracking and patient movement
- **Department Analytics** — performance and efficiency by department
- **Resource Utilization** — bed, staff, and equipment utilization

## Project Structure

```
/scripts    → data collection, cleaning, and KPI engineering notebooks
/data       → raw and processed datasets
/dashboard  → dashboard build files and storyboard
/docs       → project documentation
```

## Pipeline

```
Collect Hospital Datasets
        ↓
Data Cleaning & Transformation
        ↓
Healthcare KPI Engineering
        ↓
Dashboard Development
        ↓
Dashboard Integration
        ↓
Testing & Validation
        ↓
Documentation & Delivery
```

## KPIs

| KPI | Description |
|---|---|
| Total Admissions | Count of patient admissions |
| Occupancy Rate | Occupied beds ÷ total available beds |
| Average Length of Stay | Mean days between admission and discharge |
| Readmission Rate | Share of admissions that are readmissions |
| Bed Utilization Rate | Beds in use relative to total capacity |
| Department Efficiency Score | Composite score combining throughput, LOS, and readmissions |

## Tech Stack

| Area | Tools |
|---|---|
| Data Collection | Python, hospital & patient admission datasets |
| Data Processing | pandas, NumPy |
| Visualization | Power BI Desktop |
| Documentation | Markdown, GitHub |

## Deliverables

- Cleaned, KPI-engineered hospital dataset
- Four interactive dashboards
- Full project documentation
