

# NC State Wolfpack — Transfer Portal Analytics Tool
**Developed by JJ Eubank Basketball Analyst**

## Overview
A data-driven recruiting tool built to evaluate and rank 
transfer portal players for the NC State Wolfpack 2026-27 
roster under Head Coach Justin Gainey.

## What It Does
- Scores 220+ portal players using advanced metrics
- Weights defensive fit for Gainey's system (40%)
- Accounts for positional need based on current roster
- Three tier ranking system:
  - Tier 1: Full advanced metrics (149 players)
  - Tier 2: ON3 rating only (25 players)
  - Tier 3: Development prospects — C and PF (46 players)

## Data Sources
- Evan Miya Player Ratings (2025-26)
- ON3 Transfer Portal Rankings

## Notebooks
- 00_config — Team settings, roster, positional needs
- 01_data_exploration — Initial data review
- 02_data_cleaning — Data standardization and merging
- 03_player_rankings — Composite scoring model
- 04_team_fit — NC State system fit scoring
- 05_output — Final recruiting board and HTML report

## Output
A position-by-position recruiting board scored and ranked 
specifically for NC STATE. 

## Recruiting Board
[View NC State Recruiting Board](https://htmlpreview.github.io/?https://github.com/jeubank2-x/NCState_TransferPortalProject/blob/main/data/outputs/NC_State_Recruiting_Board.html)
