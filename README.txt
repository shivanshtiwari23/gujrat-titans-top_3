Gujarat Titans Top-Order Batting Analysis (IPL 2025–26)

A ball-by-ball batting analysis of Gujarat Titans across IPL 2025–26, focused on how much the team relies on its top-order trio:

Shubman Gill
Sai Sudharsan
Jos Buttler
View the Analysis
Live Interactive Notebook

🌐 Open here:
Live Project Website

Source Notebook

analysis.ipynb

Project Goal

This project explores one core question:

How dependent are Gujarat Titans on their top 3 batters?

Using ball-by-ball IPL data, the analysis breaks this down across:

overall team batting contribution
home vs away matches
wins vs losses
batting first vs chasing
individual player scoring by phase
Dataset

Source: Cricsheet

Matches Analysed
IPL 2025 → 14 league matches
IPL 2026 → 14 league matches

Total: 28 Gujarat Titans matches

Tools Used
Language
Python
Libraries
pandas
matplotlib
Environment
Jupyter Notebook
Visual Studio Code
Research Workflow
1. JSON Parsing

Parsed Gujarat Titans match JSON files from Cricsheet.

Extracted:

batter
runs
over
dismissal
innings
season
2. Ball-by-Ball DataFrame

Converted all deliveries into a single structured dataset for analysis.

3. Match Segmentation

Split matches into:

Home vs Away
Wins vs Losses
Batting First vs Chasing
4. Phase Analysis

Overs divided into T20 phases:

Phase	Overs
Powerplay	0–6
Middle Overs	7–15
Death Overs	16–20
Visualisations Included
Pie charts → Top 3 vs rest of batting unit
Stacked bar charts → contribution % by context
Player comparison charts → strike rate / averages
Phase-wise scoring distributions
Key Findings
Gujarat Titans are strongly top-order driven

The majority of team runs come from Gill, Sai Sudharsan and Buttler.

Away matches show higher top-order dependence

The trio contributes an even bigger share outside Ahmedabad.

Chases are powered by the top 3

GT’s successful run chases rely heavily on early top-order scoring.

Clear batting roles emerge
Sai Sudharsan

Powerplay scorer

Shubman Gill

Anchor through powerplay + middle overs

Jos Buttler

Middle-over aggressor + finisher

How to Navigate This Research

If you’re visiting the project:

Start here:

→ Open the Live Project Website

Then browse in this order:

Team-level contribution charts
Home vs Away comparison
Win vs Loss analysis
Player phase-wise scoring breakdown
Final insights & conclusions
Future Scope

Possible extensions:

compare GT with other IPL teams
partnership network analysis
boundary %
dot-ball pressure
opposition-wise trends
win probability modelling
Author

Shivansh Tiwari
Independent cricket analytics project using ball-by-ball IPL data.
