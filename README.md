# Cricket World Cup Dashboard

This is a Power BI dashboard that shows data from the Cricket World Cups (2011–2023).  
It is easy to use and helps people see team results, player stats, and match details in one place.  

---

## 📸 Dashboard Preview
![Cricket World Cup Dashboard](https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard/blob/main/Screenshot%202025-08-09%20145647.png)  

---

## Live Files & Media
- [Dashboard File (.pbix)](https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard/blob/main/World%20Cup%20Cricket%20.pbix)  
- [Dashboard Screenshot](https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard/blob/main/Screenshot%202025-08-09%20145647.png)  
- [Video of the Report](https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard/blob/main/Videos%20of%20the%20report.mp4)  

---

## Introduction / Problem
Cricket is loved by millions.  
But the data from many matches is often spread out in different places.  
This project puts match results, player information, and bowling stats together in one dashboard.  
It helps fans, coaches, and data lovers understand the game better.

---

## Project Goals
- Make a clear and interactive dashboard for Cricket World Cup data.
- Show match results, team performance, and player stats.
- Use Power Query to clean the data.
- Use DAX to create extra calculations.
- Share the dashboard so others can use it.

---

## Dataset
The project uses three main CSV files:

1. **Match Information**  
   `Match_no`, `Date`, `Venue`, `Team1`, `Team2`, `Winner`, `Scorecard URL`

2. **Player Information**  
   `player_na`, `team_na`, `image_of`, `battingSty`, `bowlingSt`, `playingRo`, `description`

3. **Bowling Statistics**  
   `Match_no`, `Match_Be`, `Bowling_`, `Bowler_N`, `Overs`, `Maidens`, `Runs`, `Wickets`, `Economy`

**Dataset Files:**
- [world_cup_players_info.csv](https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard/blob/main/world_cup_players_info.csv)  
- [match_schedule_results.csv](https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard/blob/main/match_schedule_results.csv)  
- [bowling_summary.csv](https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard/blob/main/bowling_summary.csv)  

---

## Data Preparation Process
- Loaded CSV files into Power BI.
- Cleaned data using Power Query:
  - Fixed missing values.
  - Made dates the same format.
  - Matched team names.
- Linked the tables with relationships in the data model.

---

## Features
- Pick a World Cup year and match to see details.
- View total runs, wickets, winner, and victory margin.
- See the Man of the Match and both team lineups.
- Toss winner and decision (bat or bowl).
- Interactive charts to explore more.
- Professional and simple design.

---

## Sample Insights
Here are some examples of what the dashboard can show:
- India’s win rate in World Cups from 2011–2023 was 78%.
- Spin bowlers had a lower economy rate in Asian stadiums.
- Teams batting first in finals won 60% of the time.

---

## Tools Used
- Power BI Desktop – to make the dashboard
- Power Query – to clean and prepare data
- DAX – to make new measures and columns
- GitHub – to share and store the project

---

## How to Use
1. Download or clone the repository:
   ```bash
   git clone https://github.com/sorifulislam111/Cricket-World-Cup-Dashboard.git
