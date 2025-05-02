# City Vibe Index – Real-Time Urban Sentiment Dashboard

A unique Power BI project that visualizes the "vibe" or mood of different urban zones using simulated real-time data. This interactive dashboard integrates diverse urban metrics like sentiment, noise, weather, events, and public transit to compute a composite **City Vibe Score**.

## Project Highlights

- Real-time-style simulation over 7 days of hourly data
- Dynamic visualizations (line charts, bar charts, KPIs)
- Drill-through by zone and timestamp
- Composite Vibe Score combining 5 real-world urban indicators

## Dataset

Simulated data contains:
- **Timestamp** (hourly over 7 days)
- **Zone** (Downtown, Midtown, Uptown, Suburb, Waterfront)
- **Sentiment Score** (simulated from social media analysis)
- **Noise Level (dB)** (simulated from IoT)
- **Weather Score** (0-1)
- **Event Density** (count of local events)
- **Transit Delay (min)**
- **Vibe Score** (calculated from weighted metrics)


## Power BI Dashboard Features

- Line chart of Vibe Score trends per zone
- KPI cards showing average conditions
- Top-performing zones by average vibe
- Interactive slicers for zone filtering
- Drill-through pages by zone and time

## Tools Used

- Power BI Desktop
- Python (for data simulation)
- CSV file as source
