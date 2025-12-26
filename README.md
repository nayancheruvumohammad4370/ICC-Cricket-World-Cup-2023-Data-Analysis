# Project Overview
This project provides a comprehensive analytical breakdown of the ICC Cricket World Cup 2023. The analysis transforms raw match data into actionable insights regarding team strategies, individual excellence, and the impact of external factors like venues and match situations.

# Key Features
1. Data Preprocessing & Cleaning
Standardizes column names and formats across four primary datasets (Batting, Bowling, Match Results, and Player Info).
Handles missing values and categorizes dismissal types (out vs. not out).
Integrates player roles and country information with performance summaries.

2. Team Performance Metrics
Win Percentage: Ranks teams based on their success rate throughout the tournament.
300+ Score Analysis: Identifies the teams that consistently crossed the 300-run threshold and provides their average scores.
Bowling Dominance: Tracks which teams were most successful at bowling out their opposition.

3. Batting & Bowling Depth
Batting Order Efficiency: Calculates average runs per wicket categorized by Top Order (1-3), Middle Order (4-7), and Lower Order (8+).
Bowling Economy & Strike Rates: Evaluates team bowling performance based on runs conceded per over and balls per wicket.

4. Pressure Situation Analysis
Chasing vs. Defending: Compares success rates for teams batting first versus those batting second.
Target Success Rates: Analyzes win percentages across different score brackets (e.g., Under 200, 250-299, 350+).
Clutch Performers: Identifies players with the most 50+ scores in successful run chases.

5. Venue & Toss Impact
Venue Bias: Determines which stadiums statistically favored the side batting first or the side chasing.
Scoring Trends: Ranks venues by their average first-innings score to identify high-scoring grounds.

6. Player Leaderboards
Top 10 Batsmen: Ranked by total runs, average, and strike rate.
Top 10 Bowlers: Ranked by wickets taken, economy rates, and best bowling figures.

# Technical Stack
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn

# Data Requirements
The analysis requires the following CSV files:
batting_summary.csv
bowling_summary.csv
match_schedule_results.csv
world_cup_players_info.csv
