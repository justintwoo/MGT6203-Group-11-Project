# Predicting Baseball Game Outcomes Using Historical Performance Data

## Project Overview
This project aims to predict the outcomes of baseball games by analyzing historical performance data for both home and visiting teams. The goal is to develop a model that can accurately forecast which team will win, and identify the factors that most significantly impact game outcomes, providing insights into team and player dynamics.

## Objectives
1. **Predict Game Outcomes**: Build a model to predict whether the home or visiting team will win based on historical data.
2. **Identify Key Factors**: Analyze and determine the most impactful features, such as team performance metrics and pitching stats, on game outcomes.

## Datasets
- **Raw Game Data**: Historical game logs with statistics and details for each game.
- **Filtered Dataset**: A processed version of the raw data, retaining only the columns relevant for predictive modeling.
- **Yearly Aggregated Data**: Team performance metrics aggregated by year, capturing historical win rates and performance trends.

## Key Features
- **Team Performance Metrics**: Includes stats for both home and visiting teams, such as hits, RBIs, home runs, and strikeouts.
- **Pitching Stats**: Earned runs, strikeouts, wild pitches, and balks to assess pitching influence on game outcomes.
- **Game Details**: Attendance, day/night indicators, and game type (single/double-header) for context.
- **Win Rates**: Historical win rates by team, calculated from prior games to capture recent form.

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/baseball-game-outcome-prediction.git
cd baseball-game-outcome-prediction
pip install -r requirements.txt
