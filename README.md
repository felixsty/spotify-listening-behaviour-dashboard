# Spotify Listening Behaviour Analytics (Tableau)

## Overview
This project analyzes personal Spotify Extended Streaming History data (2025) using Tableau for data visualization and insight generation.

The focus is on understanding listening behaviour, time-based patterns, artist and track preferences, and overall engagement trends throughout the year.

---

## Dataset
- Source: Spotify Extended Streaming History (personal account)
- Time period: 2025

### Columns
- `ts` — Timestamp of each streaming event  
- `artist_name` — Name of the artist  
- `track_name` — Name of the track  
- `ms_played` — Duration played in milliseconds  
- `platform` — Device or platform used  
- `reason_start` — Playback start reason  
- `reason_end` — Playback end reason  

### Data Files
- Raw dataset: `spotify_extended_history_2025.csv`

---

## Data Preparation
All data preparation was performed within Tableau, including:
- Converting timestamps to date and time fields  
- Creating calculated fields for listening duration and play counts  
- Extracting hour, day, and month for time-based aggregation  
- Handling incomplete or zero-duration plays  

---

## Analysis
- Listening patterns analyzed across hours, days, and months  
- Identification of peak listening periods and behavioural trends  
- Ranking of top artists and tracks by engagement metrics  
- All insights presented through an interactive Tableau dashboard  

---

## Visualization
- Interactive dashboard built in Tableau  
- Includes filters for time period, artist, and track  
- Designed to support exploratory analysis and insight discovery  

🔗 **View the interactive dashboard on Tableau Public**  
*(insert link here)*

---

## Skills Demonstrated
- **Tableau** — Interactive dashboards, calculated fields, and filters  
- **Data analysis** — Behavioural pattern identification and aggregation  
- **Time-series analysis** — Hourly, daily, and monthly trends  
- **Data visualisation** — Clear storytelling through dashboards  

---

## Project Structure
