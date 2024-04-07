# Football Dataset Analysis

## Overview

This project involves analyzing a football (soccer) dataset to derive various statistics for teams in the Premier League Division during the '22-23' season. The dataset contains information about matches including match date, home team, away team, full-time and half-time goals, full-time result, and match statistics such as shots, corners, fouls, and cards.

## Files

- `premier_league22_23.csv`: The original dataset containing football match data for the Premier League Division during the '22-23' season.
- `premier_league_22_23_with_points.csv`: Dataset updated with columns for home and away team points based on match results.
- `premier_league22_23.csv`: Dataset listing teams based on their total points obtained after all matches, and sorted based on overall goal difference.
- `team_statistics.csv`: Dataset containing statistics for each team including total matches played, total won, total drawn, total lost, and goal difference.

## Process

1. **Data Preparation**: Loaded the original dataset `premier_league22_23.csv` using pandas.
2. **Calculating Points and Goal Difference**: Calculated points for each match based on the match result (3 points for a win, 1 point for a draw) and calculated goal difference.
3. **Creating New Columns**: Added new columns for home and away team points based on match results.
4. **Team Statistics**: Grouped the dataset by home and away teams, calculated statistics including total matches played, total won, total drawn, total lost, and goal difference.
5. **Sorting Teams**: Sorted teams based on total points, total won, total drawn, total lost, and goal difference.
6. **Saving Results**: Saved the sorted dataset containing team statistics to `team_statistics.csv`.

## Usage

To replicate the analysis:

1. Ensure you have Python installed along with pandas library.
2. Download the original dataset `premier_league22_23.csv`.
3. Run the provided Python script to perform the analysis and generate the necessary datasets.

## Results

The resulting `team_statistics.csv` file contains detailed statistics for each team in the Premier League Division during the '22-23' season, including total matches played, total won, total drawn, total lost, and goal difference. Teams are sorted based on these statistics to provide insights into their performance during the season.

