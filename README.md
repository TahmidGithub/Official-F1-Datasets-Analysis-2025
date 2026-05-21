# 🏎️ Official F1 2025 Performance Analysis

An end-to-end data visualisation project built in **Tableau** that explores the 2025 Formula 1 season, overing team rankings, weather-based performance, pit-stop and tyre strategy, lap-time benchmarking, and circuit-level comparisons across the global calendar.

---

## 📊 Project Overview

This project transforms raw F1 timing, results, and weather data into two interactive dashboards designed to answer key questions about the 2025 season:

- Which teams are dominating, and how has their form evolved since 2022?
- Who performs best (and worst) in dry vs. wet conditions?
- How do pit-stop and lap-time efficiency vary by team and circuit?
- What tyre strategies played out at the 2025 Zandvoort Grand Prix?
- Where in the world are the fastest — and slowest — pit lanes?

The goal was to combine **storytelling, comparative analysis, and geographic context** into a polished, recruiter-ready Tableau portfolio piece.

---

## 🔗 Live Interactive Dashboards

| Dashboard | Link |
|---|---|
| **Part 1** — Rankings, Weather Performance, Lap & Stop Duration, Zandvoort Tyre Strategy | [View on Tableau Public](https://public.tableau.com/views/CW2_Final_17793696495180/Dashboard2) |
| **Part 2** — Lap Duration by Circuit & Global Pit-Stop Map | [View on Tableau Public](https://public.tableau.com/views/OfficialF12025PerfomancePart2/Dashboard2) |

---

## 🖼️ Dashboard Previews

### Dashboard 1 — Performance, Weather & Tyre Strategy
![Dashboard 1](<img width="2462" height="1109" alt="Dashboard 1" src="https://github.com/user-attachments/assets/4b093d03-fb0d-4994-b239-6c8b49a615dd" />
)

### Dashboard 2 — Circuit Lap Times & Global Pit Performance
![Dashboard 2](<img width="2462" height="1109" alt="Dashboard 2" src="https://github.com/user-attachments/assets/7dbdbd6f-edf4-43f3-aa6e-ef0e10ed9192" />
)

---

## 🔍 Key Insights

### 🏆 Rankings (2022 → 2025)
- **McLaren** has surged from ~300 points (Dec 2022) to **800+ points**, overtaking Mercedes to become the dominant constructor.
- **Mercedes** has plateaued in the 400–500 point range.
- **Alpine** and **Kick Sauber** sit at the back of the field, with Alpine in clear decline.

### 🌦️ Weather Performance
- **McLaren** and **Mercedes** earn the overwhelming majority of their points in **dry conditions** (78% and 75% respectively).
- **Kick Sauber** is uniquely reliant on **wet/mixed conditions** — over 38% of their points come from non-dry races, suggesting their car (or strategy) punches above its weight when grip is unpredictable.

### ⏱️ Lap & Stop Duration (2025)
- Despite leading the championship, **McLaren has the slowest average pit-stop duration** of the four teams analysed.
- **Mercedes** runs the fastest stops, hinting at a clear operational edge in the pit lane that doesn't fully translate to on-track points.

### 🛞 Zandvoort Tyre Strategy
- Most front-runners (NOR, PIA, RUS, ANT) ran a **Medium → Hard → Soft** strategy.
- Multiple drivers used 3–4 stints, indicating a tactically active race with several safety-car or strategy-driven pit windows.

### 🌍 Circuit-Level Lap Times (Heatmap)
- **McLaren** posts negative deltas (faster than mean) at nearly every circuit — most dramatically at **Austin (-3.79s)** and **Monaco (-2.10s)**.
- **Alpine** is consistently the slowest team on lap pace.
- **Kick Sauber's** standout anomaly is **Miami Gardens (+3.91s)** — by far their worst circuit.

### 🗺️ Global Pit-Stop Performance
- Pit-stop speeds (avg 2.9s – 4.6s) are mapped by circuit, revealing the **Italian and Middle Eastern rounds** as the slowest pit lanes of the season.

---

## 🛠️ Tools & Techniques

- **Tableau Desktop / Tableau Public** — dashboard building, parameter actions, dual-axis charts
- **Calculated Fields** — normalised rankings, weather-share percentages, lap-time deltas vs. mean
- **Mapbox / OpenStreetMap** integration for the global pit-stop map
- **Gantt-style stint chart** for tyre-strategy visualisation
- **Diverging colour palettes** (red ↔ green) for performance deltas

### Chart Types Used
- Line charts (rankings over time)
- Stacked bar charts with log scale (weather performance)
- Dual-axis bar + line (lap vs. stop duration)
- Gantt charts (tyre stints)
- Heatmap tables (circuit lap deltas)
- Symbol maps (global pit-stop speeds)

---

## 📚 Data Source

The analysis is built on the **Official F1 2025 dataset**, including race results, lap timing data, pit-stop logs, weather classifications, and circuit metadata.

---

## 👤 Author

**Tahmid**
🔗 [GitHub](https://github.com/TahmidGithub) • [Tableau Public Profile](https://public.tableau.com/)

---

## 💬 Feedback

If you spot an interesting pattern in the data or have suggestions for additional views, feel free to open an issue or reach out. Pull requests welcome.
