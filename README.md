
# Gujarat Titans Top-Order Dependency Analysis (IPL 2025–2026)

<p align="center">
  <strong>Ball-by-ball cricket analytics project investigating how dependent Gujarat Titans are on their top-order batting trio.</strong>
</p>

<p align="center">
  <a href="https://shivanshtiwari23.github.io/gujrat-titans-top_3/">
    <img src="https://img.shields.io/badge/Live%20Analysis-View%20Project-blue?style=for-the-badge">
  </a>
  <a href="https://cricsheet.org/">
    <img src="https://img.shields.io/badge/Data-Cricsheet-orange?style=for-the-badge">
  </a>
  <img src="https://img.shields.io/badge/Python-pandas%20%7C%20matplotlib-green?style=for-the-badge">
</p>

---

## Project Overview

Gujarat Titans have built one of the strongest top orders in the IPL, featuring:

* Shubman Gill
* Sai Sudharsan
* Jos Buttler

This project uses ball-by-ball IPL data to quantify how much Gujarat Titans depend on these three batters and how that dependency changes across different match situations.

The analysis combines team-level and player-level metrics to uncover patterns in scoring contribution, match outcomes, and batting phases.

---

## Live Analysis

### Explore the complete project

**🔗 [https://shivanshtiwari23.github.io/gujrat-titans-top_3/](https://shivanshtiwari23.github.io/gujrat-titans-top_3/)**

The website contains the full notebook, visualisations, methodology, and conclusions.

---

## Research Question

> **How dependent are Gujarat Titans on their top three batters?**

To answer this question, the project examines:

* Top-order vs middle/lower-order run contribution
* Home vs away performances
* Wins vs losses
* Batting first vs chasing
* Powerplay, middle overs, and death overs scoring
* Individual batting profiles of the top three

---

## Dataset

### Source

Ball-by-ball IPL data from Cricsheet.

### Matches Analysed

| Season    | Matches |
| --------- | ------: |
| IPL 2025  |      14 |
| IPL 2026  |      14 |
| **Total** |  **28** |

All analyses are based on Gujarat Titans matches from these two seasons.

---

## Methodology

The workflow followed in this project:

1. Extract IPL JSON files from Cricsheet
2. Parse ball-by-ball data
3. Construct analytical dataframes using pandas
4. Segment innings into match phases
5. Calculate player and team contributions
6. Generate visualisations
7. Interpret patterns and draw conclusions

---

## Tech Stack

| Category                | Tools            |
| ----------------------- | ---------------- |
| Programming             | Python           |
| Data Analysis           | pandas           |
| Visualisation           | matplotlib       |
| Notebook Environment    | Jupyter Notebook |
| Development Environment | VS Code          |

---

## Key Findings

### Top-Order Reliance

The Gill–Sudharsan–Buttler trio contributes a dominant share of Gujarat Titans' total runs, highlighting a clear concentration of batting responsibility.

### Greater Dependency Away From Home

The top three account for an even larger proportion of runs in away fixtures compared to matches played in Ahmedabad.

### Chasing Success Depends on the Trio

Successful run chases are strongly correlated with significant contributions from the top order.

### Distinct Batting Roles

| Player        | Primary Role               |
| ------------- | -------------------------- |
| Sai Sudharsan | Powerplay scorer           |
| Shubman Gill  | Anchor and innings builder |
| Jos Buttler   | Accelerator and finisher   |

The analysis shows a well-defined division of responsibilities within the batting unit.

---

## Suggested Reading Order

For the best experience:

1. Team contribution analysis
2. Home vs away comparison
3. Wins vs losses breakdown
4. Batting first vs chasing
5. Phase-wise player analysis
6. Final conclusions

---

## Future Enhancements

Potential extensions of this project include:

* Gujarat Titans vs other IPL teams
* Boundary percentage analysis
* Dot-ball pressure metrics
* Partnership network visualisation
* Opposition-specific trends
* Win probability modelling
* Predictive batting contribution models

---

## About the Author

### Shivansh Tiwari

Independent cricket analytics enthusiast exploring team strategy and player performance through ball-by-ball data analysis.

Built using Python, pandas, matplotlib, and Cricsheet IPL datasets.

---
