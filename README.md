# Manufacturing Equipment Downtime Analysis

## Project Overview

This project analyzes manufacturing equipment telemetry data to identify downtime patterns across factories and machine types.

The analysis was developed in Tableau to provide an interactive view of equipment downtime and help identify areas that may require further operational investigation.

## Business Problem

Manufacturing operations depend on reliable equipment availability. Frequent or prolonged equipment downtime can disrupt production and require maintenance intervention.

The objective of this analysis is to use equipment telemetry data to answer:

- Which factories experienced the highest downtime?
- Which machine types contributed the most downtime?
- How does downtime vary across factories?
- Which equipment types may require further investigation?

## Key Metrics

- **Total Downtime:** 17 hours 10 minutes
- **Downtime Events:** 103
- **Factories Analyzed:** 4
- **Machine Types Analyzed:** 9

## Dashboard
Manufacturing Equipment Downtime Dashboard <img width="1318" height="802" alt="image" src="https://github.com/user-attachments/assets/f94c3b19-42b0-487a-9c53-ea838b4adce5" />

The Tableau dashboard provides:

- Downtime by factory
- Downtime by machine type
- Interactive factory selection
- KPI metrics for overall downtime and downtime events
- Machine-level drill-down through factory selection

### Tableau Public

[View the interactive dashboard on Tableau Public](https://public.tableau.com/views/ManufacturingEquipmentDowntimeAnalysis/ManufacturingDowntimeAnalysis)

## Key Findings

The analysis shows that downtime is not evenly distributed across the factories or machine types.

The highest recorded factory downtime was associated with **Seiko**, followed by **Shenzhen**.

At the machine level, **Laser Welder** and **Laser Cutter** accounted for the largest recorded downtime totals.

The interactive dashboard allows users to select a factory and examine the equipment downtime associated with that location.

## Tools Used

- Tableau
- JSON telemetry data
- Data visualization
- Calculated fields
- Dashboard actions and interactive filtering

## Methodology

Telemetry records were analyzed to identify unhealthy equipment events.

Because telemetry messages are received at 10-minute intervals, each unhealthy telemetry event represents an estimated 10 minutes of downtime.

A calculated field was used to convert unhealthy telemetry events into downtime minutes, which were then aggregated by factory and machine type.

## Project Context

This project was completed as part of the **Deloitte Australia Data Analytics Virtual Experience Program on Forage**.

The dashboard was further refined and documented as a portfolio project to demonstrate data analysis, visualization, and dashboard development skills.

## Limitations

The analysis is based on the telemetry data provided for the simulation and should therefore be interpreted within the context of the available dataset.

The identified downtime patterns indicate areas for further investigation but do not by themselves establish the root cause of equipment failures.

## Author

**Veronica Ngatia**

Data Analyst | Tableau | SQL | Excel | Power BI
