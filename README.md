**Baseball Team Power Analysis**

Project analyzes baseball team performance, focusing on batting power, using data from the 2022, 2023, and 2024 seasons. The analysis assigns weighted importance to each season, computes power metrics for each team, and visualizes the results with MATLAB. The aim is to evaluate and compare teams based on their batting capabilities using statistical metrics.


**Overview**

The project calculates a "Power Number" for each team, a composite metric derived from key batting performance indicators. The results are visualized through bar charts, scatter plots, and regression analyses, providing insights into team performance trends over the three seasons.


**Season Weighting**

Data from three consecutive seasons are used to calculate the Power Number, with each season weighted based on its relevance:

2024: 50%
2023: 35%
2022: 15%
This weighting emphasizes the most recent season's performance while still considering the historical context.


**Metrics Used**

The following metrics form the basis of the Power Number calculation:
R/G (Runs per Game): Offensive production measured as runs scored per game.
R (Runs): Total runs scored during the season.
BA (Batting Average): Measures a player's ability to hit, calculated as hits divided by at-bats.
OBP (On-Base Percentage): A player's ability to reach base by any means.
OPS (On-Base Plus Slugging): Sum of OBP and SLG, capturing overall batting performance.
SLG (Slugging Percentage): Power-hitting ability, measured as total bases per at-bat.
SB (Stolen Bases): Aggressiveness and base-stealing proficiency.
Weights are assigned to each metric to calculate the final Power Number.


**Data Provider**

The data used in this analysis was sourced from Baseball Reference (https://www.baseball-reference.com/).

When using Baseball Reference data, please cite them and provide a link and/or a mention.


**Code and Libraries Used**

The analysis was performed using MATLAB, leveraging its capabilities for data processing, computation, and visualization. Key functions and techniques include:

Data Manipulation: Sorting, filtering, and calculating weighted metrics.
Visualization: bar, scatter, and regression line plotting using polyfit and polyval.
Scripting: MATLAB .m files for replicable workflows.
Key Visualizations
Bar Charts: Display Power Numbers for each team to compare overall batting power.
Scatter Plots: Show relationships between Runs per Game (R/G) and Power Numbers, with regression lines for trend analysis.


**Limitations and Restrictions**

While this project provides interesting insights, it has many significant limitations:

Focus on Batting Power:
This analysis exclusively evaluates batting metrics, overlooking pitching performance, which is equally critical for a successful season. Teams with excellent batting but poor pitching often struggle to achieve strong results.

No Consideration of Player Market Dynamics:
The analysis does not factor in off-season trades, acquisitions, or injuries, which can significantly alter a team's lineup and performance between seasons.

Data Source Constraints:
The Power Numbers are based solely on past performance statistics, limiting the ability to predict future outcomes with high accuracy. Teams often evolve, and historical data may not reflect their current potential.

Simplified Assumptions:
Assigning weights to metrics and seasons involves assumptions that may not fully capture the nuances of team performance.


**Future Improvements**

Incorporating pitching metrics to provide a more holistic view of team performance.
Adding a module for player market analysis to account for off-season changes.
Including advanced metrics such as WAR (Wins Above Replacement) or wOBA (Weighted On-Base Average) for deeper insights.
Using machine learning models to predict team performance based on historical and contextual data.
