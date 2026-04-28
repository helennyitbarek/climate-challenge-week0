# Climate Data Analysis for African Countries

## Business Objective

This project is developed for EthioClimate Analytics as part of the Junior Data Analyst role.

The goal is to analyze climate data across five African countries to identify temperature and rainfall trends that support climate risk assessment for COP32 discussions.

---

## Project Structure

- notebooks/ → Country-specific EDA notebooks
- data/ → Raw datasets
- scripts/ → Helper scripts
- requirements.txt → Dependencies
- .github/workflows/ → CI pipeline

---

## Task 1: Git & Environment Setup

- Initialized Git repository
- Created feature branches for development
- Implemented GitHub Actions CI workflow
- Added .gitignore to exclude unnecessary files (venv, data, cache)
- Followed conventional commit standards (feat, fix, chore)

---

## Task 2: Data Cleaning & EDA

Exploratory Data Analysis was performed for the following countries:

- Kenya
- Tanzania
- Sudan
- Nigeria
- Ethiopia

Each notebook includes:
- Data loading
- Data cleaning (missing values, type conversion)
- Exploratory analysis
- Visualizations of temperature and rainfall trends
- Basic insights per country

---

## Key Insights

- Climate patterns vary significantly across countries
- Temperature shows seasonal and long-term trends
- Data cleaning was necessary before meaningful analysis

---

## Next Steps

- Build climate vulnerability ranking model
- Develop interactive dashboard for insights
- Extend analysis with forecasting techniques
- Compare climate patterns across regions