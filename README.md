# F1 Spatial Telemetry Analysis 🏎️📊

This project extracts and structures spatial telemetry data (X,Y GPS coordinates) from Formula 1 cars to analyze racing lines and speed profiles.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** FastF1, Pandas
- **GIS Software:** QGIS (for spatial visualization and mapping)

## 📍 Project Overview
Using telemetry tracking, this dataset maps out the precise coordinates against vehicle speed for analysis in GIS environments.

## 📂 Data Structure
- `X`, `Y`: Spatial coordinates of the car on the track (in meters).
- `Speed`: Vehicle speed at that exact point (km/h).
- `Throttle` / `Brake`: Driver inputs mapped to geography.
