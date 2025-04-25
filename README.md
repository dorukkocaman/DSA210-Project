# NBA Assist/Turnover Ratio Analysis

## Hello my name is Doruk Kocaman. My main goal is to examine assist / turnover ratio withh the win percentage of the team and points per game. 


## Project Overview

In this project, I investigated whether a basketball team's **Assist/Turnover (AST/TO) ratio** is related to two important performance metrics:

- **Points Per Game (PTS/Game)**
- **Win Percentage (Win%)**

My goal was to find out if teams that move the ball better and take care of possessions (i.e., have a high assist/turnover ratio) tend to **score more points** and **win more games**.

---

## Methodology

- I used a dataset containing NBA team statistics from the **2000-01** season to the **2022-23** season.
- For each team, I calculated:
  - **Total Assists** and **Total Turnovers**
  - **Total Points Scored**
  - **Total Games Played**
  - **Total Wins**
- Then, I derived the following key metrics:
  - **Assist/Turnover Ratio** = Total Assists / Total Turnovers
  - **Points Per Game** = Total Points / Total Games Played
  - **Win Percentage** = Total Wins / Total Games Played

- I visualized the results using a combined plot:
  - Bars represent each team's Assist/Turnover ratio
  - Lines represent Points Per Game and Win Percentage

---

## Key Findings

- There is a **moderate positive correlation** between Assist/Turnover Ratio and Points Per Game.
- Teams with better ball movement and fewer turnovers tend to **score more points**.
- The relationship between Assist/Turnover Ratio and Win Percentage also exists, but it is **less strong** compared to Points Per Game.
- Other factors (such as defense) likely influence winning beyond just offensive efficiency.

---

## Conclusion

Ball movement and possession efficiency (as measured by Assist/Turnover ratio) are important factors for scoring in the NBA.  
While they contribute to winning, **they are not the only elements** that determine a team's success.

This project helped me understand how small metrics like assist/turnover ratios can have a meaningful but partial impact on broader performance outcomes.

---

## Future Work

- Performing year-by-year analyses to observe trends over time.
- Running a multivariable regression including defensive stats.
- Comparing playoff vs regular season behaviors.

---

## Example Visualization



> Note: The graph shows the Assist/Turnover ratio as bars, while Points Per Game and Win Percentage are plotted as lines for each team, based on data from 2000 to 2023.





