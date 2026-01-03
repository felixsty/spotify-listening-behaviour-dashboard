# Spotify Listening Behaviour Analytics (Tableau)

## Overview
This project analyzes personal Spotify Extended Streaming History data (2025) using **Tableau** for data preparation, analysis, and visualization.  
The focus is on understanding listening behaviour, time-based engagement patterns, and artist and track preferences across the year.

---

## Dataset

- Source: Spotify Extended Streaming History (personal account).
- Time period: 2025.
- Columns:
  - `ts` – Timestamp of each streaming event
  - `artist_name` – Name of the artist
  - `track_name` – Name of the track
  - `ms_played` – Duration played in milliseconds
  - `platform` – Device or platform used
  - `reason_start` – Playback start reason
  - `reason_end` – Playback end reason
- Raw dataset: `spotify_extended_history_2025.csv`

---

## Data Preparation (Tableau)

All data preparation was performed within Tableau, including:

- Converting timestamps to **date** and **time** fields.
- Creating calculated fields for listening duration and play counts.
- Extracting hour, day, and month fields for time-based aggregation.
- Handling incomplete and zero-duration streaming records.

---

## Analysis

- Analysis focused on **listening patterns, engagement trends, and content preferences**.
- Time-series analysis was used to identify peak listening hours and seasonal trends.
- Artist and track rankings were created based on listening duration and frequency.
- All analysis outputs are presented through an interactive Tableau dashboard.

---

## Visualization

- Interactive dashboard built using Tableau.
- Includes filters for time period, artist, and track.
- Designed to support exploratory analysis and insight discovery.

🔗 **Tableau Public dashboard:** *(insert link here)*

---

## Skills Demonstrated

- Tableau: interactive dashboards, calculated fields, and filters
- Data analysis: behavioural pattern identification and aggregation
- Time-series analysis: hourly, daily, and monthly trends
- Data visualization: clear insight storytelling through dashboards

---

## Project Structure

```
spotify-listening-behaviour/
│
├── spotify_dashboard.twbx                   # Tableau packaged workbook
├── spotify_extended_history_2025.csv        # Dataset
|
├── images/
│   └── dashboard_overview.png               # Dashboard preview
|
└── README.md                                # Project background and overview
```

---

This repo demonstrates a **complete analytics workflow**:  
**data extraction → data preparation → analysis → data visualization**
