# NFL Live Strength of Schedule

A project to compute a weekly-updating strength of schedule metric using current-season NFL results.


## Purpose

Strength of Schedule metrics are often used in the preseason to project team performance, and in the postseason to decide tiebreakers. 
But during the season, there is value in understanding how hard a team's schedule has been, and how hard it will be for the rest of the season.

This tool is aimed at creating a live SOS metric that:
* Ranks teams' SOS based on the difficulty of games they've played that season
* Projects a "Remaining SOS" with statistics that update weekly.


## Data Sources

Data types to be included:

* Current season records
* Team statistics
  * Offensive \& Defensive EPA
  * Point differential
  * Run/Pass Percentage

Data sources:

* nflreadpy
* Supplemental CSVs (WIP)


## Methodology

This project does not attempt to rank teams by overall quality. Instead, it evaluates the quality of a team’s opponents using current-season performance metrics that evolve weekly. Teams are ranked by strength on a week-to-week basis, and those rankings are then used to assess the difficulty of the schedules they face.

## Project Status

In progress:

Data fetching