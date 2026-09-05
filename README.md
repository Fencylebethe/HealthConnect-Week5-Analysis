# HealthConnect Clinic – Week 5 Analysis

## AnalystLab Africa | Data Analytics Internship (Batch D)

This repository contains my Week 5 submission for the AnalystLab Africa Experience Lab, continuing the HealthConnect Clinic project: *Improving Patient Appointment Attendance and Healthcare Support Using Data and AI*.

## Project Background

Week 4 established the foundation for this project: a full data quality assessment, three business questions, and four proposed KPIs relating to appointment no-shows. Week 5 moves from planning into practical analysis — calculating KPIs, visualising results, and producing actionable business insights.

## Week 5 Focus (Data Analytics Track)

- Prepared the dataset for analysis (data types, missing values, duplicates confirmed clean; new lead_time_bracket column created)
- Conducted exploratory data analysis on appointment attendance and no-show patterns
- Calculated and visualised three KPIs using Power BI (DAX measures and calculated columns)
- Produced 5 business insights and 4 practical recommendations for HealthConnect Clinic
- Documented a cross-track collaboration point with the Data Science track

## Files in This Repository

| File | Description |
|---|---|
| `HealthConnect_Week5_Analysis.docx` | Full Week 5 write-up: Week 4 recap, data preparation, EDA, KPI calculations, visualisations, business insights, recommendations, limitations, cross-track collaboration, and project summary |
| `HealthConnect_Week5_Analysis.pbix` | Power BI file containing the three KPI visualisations and underlying DAX calculations |

## Key Findings

- **Booking lead time** is the strongest predictor of no-shows: patients booking 31+ days in advance no-show at **75.81%**, nearly 3x the rate of those booking within a week (**27.81%**)
- **Previous no-show history** is highly predictive: no-show rate climbs steadily from **43.51%** (no prior no-shows) to **100%** (5 prior no-shows)
- **Appointment type** has minimal influence on no-show behaviour, with all four types falling within a narrow 44.64%–51.23% range

## Business Recommendations

1. Escalate reminder intensity for appointments booked 31+ days in advance
2. Flag patients with 2+ previous no-shows for extra confirmation steps
3. Simplify the cancellation process to convert more no-shows into cancellations
4. Prioritise booking lead time and no-show history over appointment type when designing interventions

## Next Steps (Week 6)

Multi-variable analysis combining booking lead time and previous no-show history, and calculation of the remaining KPI on appointment time slot.

## Author

Ofentse Lebethe — Data Analytics Intern, AnalystLab Africa (Batch D)
