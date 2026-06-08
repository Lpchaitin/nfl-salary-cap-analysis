# NFL Salary Cap Analysis

## Overview
This project analyzes NFL salary cap efficiency — identifying which teams, positions, and acquisition methods produce the most on-field value per dollar spent. Using contract and performance data from 2016-2025, we build a framework for evaluating roster construction decisions through a cap efficiency lens.

## Key Questions
- Which teams get the most production per cap dollar?
- Which positions are most overpaid and underpaid relative to performance?
- How does dead cap money affect team success?
- Which is more efficient — the draft or free agency?
- What do the most cap-efficient rosters look like?

## Repo Structure
nfl-salary-cap-analysis/
├── data/
│   ├── raw/              # Raw data files (not tracked)
│   └── processed/        # Cleaned datasets (not tracked)
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_contract_value.ipynb
│   ├── 03_team_efficiency.ipynb
│   ├── 04_dead_cap.ipynb
│   ├── 05_draft_vs_fa.ipynb
│   └── 06_cap_optimization.ipynb
├── outputs/
│   └── figures/
├── src/
├── requirements.txt
└── README.md

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebooks in order: `01 → 06`
4. Data downloads automatically in notebook 01

## Data Source
Contract and roster data pulled via [nfl_data_py](https://github.com/nflverse/nfl_data_py) — credit to the nflverse contributors.