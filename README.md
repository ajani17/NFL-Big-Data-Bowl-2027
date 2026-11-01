# NFL Big Data Bowl 2027

An NFL analytics project developed for the **NFL Big Data Bowl 2027**, using NFL Combine data, player tracking data, and statistical modeling to investigate how athletic performance translates to on-field success.

## Project Overview

The goal of this project is to explore relationships between player movement characteristics, athletic testing, and NFL performance.

Our approach will combine exploratory data analysis, feature engineering, statistical modeling, and football-specific insights to identify meaningful patterns in player evaluation.

**Competition:** [NFL Big Data Bowl 2027 — Kaggle](https://www.kaggle.com/competitions/nfl-big-data-bowl-2027)

## Data

The project uses nine datasets provided through the competition:

| Dataset | Description |
|---|---|
| `players.csv` | Player information and characteristics |
| `combine_results.csv` | NFL Combine testing results |
| `combine_tracking.csv` | Player movement tracking during Combine drills |
| `player_career_successes.csv` | Career performance outcomes |
| `player_play.csv` | Player-level play information |
| `games.csv` | NFL game metadata |
| `game_tracking_2023.csv` | NFL tracking data for the 2023 season |
| `game_tracking_2024.csv` | NFL tracking data for the 2024 season |
| `game_tracking_2025.csv` | NFL tracking data for the 2025 season |

*Data is provided by the NFL through Kaggle. Raw competition datasets are not stored in this repository.*

## Tools & Technologies

- **Python:** Data processing, visualization, and modeling
- **Pandas / NumPy:** Data manipulation
- **Matplotlib / Seaborn:** Exploratory visualizations
- **Scikit-learn:** Statistical modeling and machine learning
- **Kaggle:** Dataset access and notebook execution
- **GitHub:** Version control and collaboration
- **OpenAI Codex:** AI-assisted development and code review

## Project Structure

Proposed organization as development progresses:

```text
nfl-big-data-bowl-2027/
├── README.md
├── .gitignore
├── requirements.txt
├── notebooks/
│   └── exploratory_analysis.ipynb
├── src/
│   ├── data_processing.py
│   ├── feature_engineering.py
│   └── modeling.py
├── docs/
│   └── data_dictionary.md
└── outputs/
    └── figures/
```

## Research Questions

Initial questions to explore:

1. Which NFL Combine measurements best predict on-field performance?
2. Do movement characteristics provide additional predictive value beyond traditional Combine metrics?
3. How do relationships between athletic testing and NFL performance differ by position?
4. Can tracking-derived features identify player traits that traditional testing overlooks?
5. How can findings be translated into actionable football insights?

These questions are preliminary and will be refined as the project develops.

## Development Workflow

1. Access competition datasets through Kaggle.
2. Explore the data and validate relationships between datasets.
3. Develop and test hypotheses using Python notebooks.
4. Use Codex to assist with feature engineering, analysis, and code review.
5. Version-control code and documentation through GitHub.
6. Produce reproducible visualizations and communicate findings.

## Project Status

**Current phase:** Initial setup and data exploration.

Research hypotheses, modeling methods, and final deliverables are under development.

## Data Usage

All NFL competition data is subject to the applicable Kaggle competition rules and data-use restrictions. Refer to the official competition page for details.
