# 🚲 Bike-Sharing Time Intelligence Analysis

A 5-page interactive Power BI report analysing bike-sharing trip data across multiple stations,
bike types, and time periods from 2023 to 2025.

---

## Project Summary

This report applies **DAX time intelligence functions** to uncover trends, seasonal patterns,
and performance shifts in a bike-sharing network. It was built as part of a Business Analytics
coursework assignment.

---

## Dashboard Pages

| Page | Description |
|---|---|
| **Cover** | Title page with project overview |
| **Descriptive Analysis** | KPI cards, trips by station (donut chart), trips by bike type |
| **Time-Based Analysis** | Day-over-day change, year-over-year, quarter-over-quarter, month-over-month comparisons |
| **Trend & Seasonal Analysis** | Trips by month, day of week, bike type trends across 2023–2025 |
| **Analytical Interpretation** | Weekend vs weekday analysis, month-over-month change, station performance over time |

---

## Key Metrics

- **341,390** total distance travelled
- **55,000** total trips recorded
- **39.40** minutes average trip duration
- **7 stations** analysed: Hospital, Tech Hub, Mall, Central Park, University, Airport, Downtown
- **2 bike types**: Standard (41K trips) vs Electric (14K trips)

---

## Key Insights

- Trip volumes remained **consistent year-over-year** (≈18.2K–18.3K per year) suggesting a stable user base
- **Weekday trips (39K) significantly outpace weekend trips (16K)** — indicating commuter-driven usage
- **August and July** are peak months; **January and February** see the lowest demand
- All 7 stations show **nearly equal market share** (~14% each), pointing to well-distributed infrastructure
- Standard bikes dominate usage at **3× the volume** of electric bikes

---

## Tools & Techniques

- **Power BI Desktop** — report design and visualisation
- **DAX Time Intelligence** — `PREVIOUSMONTH`, `PREVIOUSQUARTER`, `PREVIOUSYEAR`, `DATEADD`
- **Custom Date Table** — for accurate time-based calculations
- **Calculated measures** — Day-over-Day Change, Month-over-Month Change, IsWeekend flag

---

## Files

| File | Description |
|---|---|
| `Christabel_kabukie_Chrappah_11207632.pbix` | Power BI source file |
| `BIKE_SHARING_TIME_INTELLIGENCE_ANALYSIS.pdf` | Exported PDF report (all 5 pages) |

---

## Disclaimer

This project was completed as part of BSc Administration (Business Analytics) coursework.
Data used is for educational purposes only.
