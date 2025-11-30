# 🚦 Real-Time Traffic Data Pipeline on Azure

A fully automated **real-time data engineering pipeline** built on Microsoft Azure.

## Architecture Overview
Azure Maps → Function App → Event Hubs → Stream Analytics → Power BI  
SQL Database → Future ML Model

## Project Description
Real-time traffic data streaming, processing, storage, and dashboard visualization.

## Objectives
- Stream and process live data  
- Store structured SQL data  
- Visualize KPIs in Power BI  
- Prepare for future ML models  

## Tools & Technologies
Azure Maps, Event Hubs, Stream Analytics, SQL Database, Power BI, Python, SQL.

## Database Design
Table: **TrafficData**

| Field | Type | Description |
|-------|------|-------------|
| city | VARCHAR | City name |
| latitude | FLOAT | Latitude |
| longitude | FLOAT | Longitude |
| description | NVARCHAR | Incident description |
| incident_count | INT | Aggregated count |
| timestamp | DATETIME | Event time |
| window_end | DATETIME | Aggregation window |

## Power BI Dashboard
Includes map, KPIs, line charts, bar charts, gauges, and incident tables.

## Future Enhancements
- Predictive ML  
- Anomaly detection  
- IoT integration  
"""
