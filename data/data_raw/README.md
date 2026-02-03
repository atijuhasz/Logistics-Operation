# Data Source
The dataset used in this project is from Kaggle.  
![Source](https://www.kaggle.com/datasets/yogape/logistics-operations-database/data)  

The raw data files are not included in this repository due to file size limits.

# Data Overview

This database tracks **logistics operations from 2022–2024**, covering drivers, equipment, shipments, and operational performance data.

---

## Core Tables (Master Data)

These tables contain relatively static reference information.

| File | Description | Records |
|------|-------------|---------|
| **drivers.csv** | Driver details and attributes | 150 |
| **trucks.csv** | Fleet truck inventory | 120 |
| **trailers.csv** | Trailer inventory | 180 |
| **customers.csv** | Customer information | 200 |
| **facilities.csv** | Facility and location details | 50 |
| **routes.csv** | Route definitions and lane information | 57 |

---

## Transaction Tables (Operational Data)

These tables capture day-to-day logistics activity.

| File | Description | Records |
|------|-------------|---------|
| **loads.csv** | Shipment bookings and load details | 57,096 |
| **trips.csv** | Shipment execution and trip records | 57,096 |
| **fuel_purchases.csv** | Fuel transaction records | 131,120 |
| **maintenance_records.csv** | Equipment maintenance history | 6,533 |
| **delivery_events.csv** | Pickup and delivery timestamps | 114,192 |
| **safety_incidents.csv** | Safety and incident reports | 114 |

---

## Aggregated Metrics (Pre-Computed Performance)

These tables contain summarized monthly performance indicators.

| File | Description | Records |
|------|-------------|---------|
| **driver_monthly_metrics.csv** | Monthly driver performance metrics | 4,914 |
| **truck_utilization_metrics.csv** | Monthly equipment utilization metrics | 4,213 |

---


