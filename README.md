# Football_Match_Analysis

## Core Match Analysis — Spain 3–3 Portugal (WC 2018)

**Goal:** Reproduce a professional post-match analyst report with xG timelines, shot maps, passing networks, and coaching insights.

## Data
- Source: StatsBomb Open Data (competition_id=43, season_id=3)
- Access via `statsbombpy`.

## Methods
- Event parsing → shots, passes, pressures
- Visuals: mplsoccer + matplotlib
- Networks: passer→recipient edges, avg locations, phase splits

## Deliverables
- `figs/*.png` (xG timelines, shots, networks)
- `report.md` (export to PDF)
- `notebook.ipynb` (reproducible code)

## How to run
```bash
pip install -r requirements.txt
# open notebook and run all
