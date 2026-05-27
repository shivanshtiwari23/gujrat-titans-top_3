Gujarat Titans Batting Analysis (IPL 2025–2026)
Overview

This project is a data-driven batting analysis of Gujarat Titans across the IPL 2025 and IPL 2026 league stages, with special focus on the team’s dependence on its top-order batting trio:

Shubman Gill
B Sai Sudharsan
Jos Buttler

Using ball-by-ball match JSON data from Cricsheet, this project investigates:

How much of Gujarat Titans’ batting output comes from the top 3
Whether GT is overly top-order dependent
How this changes by venue, innings situation, and result
Individual scoring profiles of Gill / Sai / Buttler by batting phase
GT’s win/loss patterns in relation to top-order contribution
Dataset

Source:

Cricsheet JSON data

Dataset used:

Gujarat Titans match JSON archive
Ball-by-ball IPL match data in JSON format

Total matches available in archive: 74

For this analysis:

IPL 2025 → 14 league-stage matches used
IPL 2026 → 14 league-stage matches used

Total analysed:

28 league-stage matches

Playoff matches were excluded from season-comparison analysis where required.

Project Objectives

This project attempts to answer:

Team-Level Questions
How top-heavy is Gujarat Titans’ batting?
What % of total runs are scored by the top 3?
How much do the remaining batters contribute?
Venue-Based Questions
Does GT depend more on the top 3 at home or away?
Does Ahmedabad batting differ from away batting?
Match Context Questions
How does top-3 contribution change:
in wins?
in losses?
batting first?
chasing?
Player-Level Questions

For Gill, Sai and Buttler:

Runs scored in Powerplay (0–6)
Runs scored in Middle Overs (7–15)
Runs scored in Death Overs (16–20)
Balls faced in each phase
Strike Rate by phase
Batting Average by phase
Tech Stack
Language
Python
Development Environment
Visual Studio Code
Jupyter Notebook (.ipynb)
Libraries Used
Data Processing
pandas
Used for:
DataFrames
grouping
aggregations
filtering
match-by-match analysis
Visualisation
Matplotlib

Used for:

Pie charts
Bar graphs
Horizontal stacked charts
Percentage contribution visualisations
Methodology
1. JSON Parsing

Each Gujarat Titans JSON file was parsed manually.

Important fields extracted:

season
match_id
batting_team
batter
runs
over
player_dismissed

This enabled ball-by-ball structured analysis.

2. DataFrame Construction

A consolidated ball-by-ball DataFrame was created from all GT matches.

Each row represents a single delivery.

3. Match Segmentation

Matches were segmented into:

Home vs Away
Won vs Lost
Batting First vs Batting Second
4. Phase Segmentation

Overs were split into standard T20 phases:

Phase	Overs
Powerplay	0–6
Middle Overs	7–15
Death Overs	16–20
5. Trio Contribution Analysis

Top-order trio defined as:

Gill
Sai Sudharsan
Buttler

Measured against:

Trio Runs vs Rest of Team Runs

across all contexts.

Visualisations Used
1. Pie Charts

Used to compare:

Top 3 Runs vs Rest of Team Runs

Across:

Home matches
Away matches
Wins
Losses
Full seasons
Combined 2025–26
2. Stacked Bar Charts

Used to compare:

Top 3 % contribution vs Rest % contribution

Across match situations.

3. Player Comparison Bar Graphs

Used for:

Batting Average by phase
Strike Rate by phase
Runs scored by player in wins vs losses
4. Phase Distribution Horizontal Bars

Used to visualize:

What % of each batter’s runs come in:
- Powerplay
- Middle Overs
- Death Overs

for:

Gill
Sai Sudharsan
Buttler
Key Findings
1. Gujarat Titans are heavily top-order dependent

Across IPL 2025–26:

Gill + Sai + Buttler contribute a dominant share of total GT runs.

This confirms GT as one of the most top-3 dependent batting units.

2. Away dependency is stronger than home dependency

The top 3 contribute an even larger percentage of runs in away fixtures compared to Ahmedabad.

3. GT’s chases are heavily driven by the top 3

In successful run-chases, the trio contributes a very high share of the total.

4. Distinct player roles emerge
B Sai Sudharsan

Strongest powerplay contributor.

Shubman Gill

Anchor through powerplay + middle overs.

Jos Buttler

Middle-over accelerator and death-over finisher.

These complementary roles explain why the trio functions so effectively together.

How to Run
Clone repo
git clone <repo-url>
Install dependencies
pip install pandas matplotlib
Open notebook
analysis.ipynb

Run all cells.

Future Scope

Possible extensions:

Compare GT top-3 dependency with other IPL teams
Compare GT 2022–2026 evolution
Opposition-wise analysis
Batter partnerships network analysis
Boundary % analysis
Dot-ball pressure analysis
Win probability modelling
Author

Created by Shivansh Tiwari

Independent cricket analytics project exploring Gujarat Titans batting trends through ball-by-ball IPL data.
