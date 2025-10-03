# Aviation Risk Assessment: Data-Driven Fleet Strategy
## Overview
This repository contains a comprehensive analysis of global aircraft incidents (1990–2016) to provide data-driven insights for safer fleet investment and operational decisions. Using structured data and visualization techniques, the project identifies high-risk aircraft, operators, and geographic regions, enabling strategic, evidence-based decision-making.
## Business Understanding
**Stakeholders**
- Aviation Division Leadership
- Fleet Procurement Teams
- Risk Management Departments
**Key Business Questions**
1. Which aircraft models are associated with the highest risk of fatalities or injuries?
2. Which airline operators have historically exhibited higher incident rates?
3. Are there specific geographic regions or airports where incidents are concentrated?
4. How can this information guide safer fleet acquisition and operational planning?
## Data Understanding and Analysis
**Source of Data**
- World Aircraft Accident Summary (WAAS) database, publicly available records (1990–2016).
**Description of Data**
- **Rows:** 607 aircraft incident records
- **Columns;**
  - `WAAS Subset Event Id` – Unique event identifier
  - `Local Event Date` – Date of occurrence
  - `Aircraft` – Aircraft model
  - `Aircraft Operator` – Airline/operator
  - `Event Location` – City/country of incident
  - `Crew Fatalities`, `Crew Injured`, `Crew Aboard` – Crew impact metrics
  - `PAX Fatalities`, `PAX Injuries`, `PAX Aboard` – Passenger impact metrics
**Visualizations**
1. **Aircraft Risk Breakdown:** Bar chart showing fatality rates by aircraft model.
2. **Operator Risk Comparison:** Horizontal bar chart of total fatalities per airline operator.
3. **Geographic Hotspots:** Bubble map highlighting cities with high incident counts.
## Conclusion
**Summary of Key Findings**
1. **High-Risk Aircraft:** Boeing 737 variants show higher fatalities per incident; Embraer and Airbus models demonstrate lower risk.
2. **Operator Patterns:** Certain operators (e.g., China Airlines) have significantly higher historical incident rates; safer operators include Philippine Airlines and American Airlines.
3. **Geographic Concentration:** Guangzhou and Bangalore emerged as hotspot regions, whereas US and European locations show fewer severe incidents.
**Recommendation**  
Use these insights to prioritize low-risk aircraft, partner with safer operators, and strategically locate operations to minimize exposure.
