# Cricket Champions Trophy Data Analytics Dashboard

## Overview
This project presents a Power BI dashboard built on ICC Champions Trophy data.  
It includes data preprocessing using Python (Pandas) and visualization of match results, player performance, and team statistics.

## Tech Stack
- Python (Pandas)
- Power BI
- CSV Files

## Datasets

### Player Dataset
File: `all_champions_trophy_players_list.csv`

Columns:
- Team
- Year
- Player Name

### Match Dataset
File: `all_champions_trophy_matches_results-updated.csv`

Columns:
- Team1, Team2, Toss, Match days, Winner
- Player of the Match, Margin, Ground, Match Date
- ODI Int Match
- Team1 Avg Batting Ranking, Team2 Avg Batting Ranking
- Team1 Avg Bowling Ranking, Team2 Avg Bowling Ranking
- Team1 Total CTs participated, Team1 Total CTs won
- Team2 Total CTs participated, Team2 Total CTs won
- Team1 W/L ratio over Team2

## Data Processing
- Removed missing and duplicate values
- Standardized formats
- Prepared data for visualization

## Dashboard Features
- Team performance analysis
- Toss vs match result
- Player of the Match insights
- Venue-based trends
- Match type comparison

## Key Insights
- Toss outcome influences match results
- Certain players frequently win Player of the Match
- Match results vary across different grounds
- Rankings impact team performance
- Historical stats and W/L ratio affect outcomes

## Usage
1. Clone the repository
2. Open the `.pbix` file in Power BI
3. Explore the dashboard

## Project Structure
```
data/
dashboard/
notebooks/
README.md
```

## Author
Smithesh Shetty  
https://github.com/smithesh-shetty
