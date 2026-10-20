# ✈️ Delayed Flights Dashboard

An interactive Power BI dashboard that analyzes flight delays: which airlines and airports are most affected, how delays change over time, and what causes them.

<img width="410" height="233" alt="image" src="https://github.com/user-attachments/assets/0c6c7b33-05e4-4e63-aee5-b22551844776" />
<img width="116" height="86" alt="image" src="https://github.com/user-attachments/assets/3f2c64f6-5061-4a7f-a9f6-d29145fe2189" />
<img width="405" height="238" alt="image" src="https://github.com/user-attachments/assets/bc7ef261-76d4-40e4-9ee7-af57d1560199" />

## 📌 Project Overview

Flight delays cost airlines and passengers time and money. This project explores a large flight dataset to answer:

- Which airlines have the highest total and average delays?
- Which origin airports handle the most flights and delays?
- How do delays trend over time?
- What are the main causes of delay (weather, security, NAS, late aircraft, etc.)?

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Flights | ~2M |
| Avg Departure Delay | 43.19 min |
| On-Time Flights | 213K |
| Total Positive Delay | 82.60M min |
| Max Delay | 2.46K min |
| Min Delay | -109 min (early departure) |

## 🔍 Dashboard Contents

- **Total Positive Delay by Carrier:** ranks airlines by total delay minutes.
- **Total Flights by Date:** daily flight volume trend.
- **Total Flights by Origin:** busiest departure airports.
- **Avg Arrival vs Avg Departure Delay by Carrier:** compares both delay types.
- **Distribution of Flight Delay Causes:** share of each delay reason.
- **Interactive filtering:** select a carrier to update all visuals.

## 🛠️ Tools & Technologies

- Power BI Desktop
- DAX (measures and calculated columns)
- Power Query (data cleaning and transformation)

## 📁 Repository Structure

```
├── DelayedFlights.pbix      # Power BI report file
├── data/                    # Dataset (or link to source)
├── images/                  # Dashboard screenshots
└── README.md
