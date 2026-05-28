

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

## Methodology & Weight Decisions

**Defensive Weight (40%)**
Coach Gainey posted top 3 national defensive efficiency ratings in 
all 3 years as coordinator at Tennessee. This roster needs to 
be built around that identity first.

**Positional Need (20%)**
NC State has one true center in Kyle Evans and limited SF depth 
behind Paul McNeil and RJ Keene. The model automatically 
prioritizes players at positions of greatest need.

**Offensive Weight (20%)**
Coach Driscoll built a national identity at UNF around pace and 
3-point shooting. Offensive fit matters but comes second to 
defensive identity.

**3PT Tendency (10%)**
Weighted lower because the current roster already has strong 
3PT shooters in Hammond (39.3%), Yalaho (39.8%), and McNeil 
(42.7%). New additions do not need to fill that role.

**Competition Adjustment (10%)**
Players from stronger conferences get a boost. ACC readiness 
matters when evaluating portal targets.

## Data Limitations
Model accuracy would improve with access to shot type data, 
NIL valuations, and direct collaboration with coaching staff 
on system priorities and roster vision.

## Output
A position-by-position recruiting board scored and ranked 
specifically for NC STATE. 

## Recruiting Board
[View NC State Recruiting Board](https://htmlpreview.github.io/?https://github.com/jeubank2-x/NCState_TransferPortalProject/blob/main/data/outputs/NC_State_Recruiting_Board.html)
