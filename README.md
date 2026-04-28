# Climate Data Analysis for African Countries

## Business Objective
This project is developed for **EthioClimate Analytics** as part of the Junior Data Analyst role.

The goal is to analyze climate data across five African countries to identify temperature, precipitation, and extreme weather patterns that support climate risk assessment for COP32 discussions and inform vulnerability-based climate finance decisions.



## Project Structure

- `notebooks/` → Country-specific EDA and comparative analysis notebooks  
- `data/` → Raw and cleaned datasets  
- `scripts/` → Helper scripts for preprocessing and analysis  
- `requirements.txt` → Project dependencies  
- `.github/workflows/` → CI/CD pipeline configuration  

## Task 1: Git & Environment Setup
- Initialized Git repository with structured branching workflow
- Created feature branches for development (`main`, `compare-countries`)
- Implemented GitHub Actions CI pipeline for automated testing
- Added `.gitignore` to exclude venv, cache, and large files
- Used conventional commit messages (`feat`, `fix`, `chor

## Task 2: Data Cleaning & Exploratory Data Analysis (EDA)

EDA was performed for five African countries:
- Kenya  
- Tanzania  
- Sudan  
- Nigeria  
- Ethiopia  

Each notebook includes:
- Data loading and inspection  
- Missing value handling and type conversion  
- Feature engineering (YEAR, MONTH extraction)  
- Visualization of temperature and precipitation trends  
- Country-level insights into climate behavior  

### Key Insights (Task 2)
- Climate variability differs significantly across countries  
- Temperature shows clear seasonal and inter-annual trends  
- Precipitation is highly irregular in some regions  
- Data required cleaning before meaningful comparison  



## Task 3: Cross-Country Climate Comparison & Vulnerability Ranking

A unified dataset was created by combining all five countries to perform comparative analysis.

### Analysis Performed:
- Monthly average temperature comparison across countries  
- Precipitation variability using boxplots  
- Extreme heat frequency (T2M > 35°C)  
- Dry day frequency (PRECTOTCORR < 1 mm)  
- Statistical summary (mean, median, standard deviation)  

### Climate Vulnerability Ranking:
Countries were ranked based on:
- Temperature variability  
- Precipitation instability  
- Frequency of extreme heat and drought events  

### COP32 Insights:
- Identified countries experiencing faster warming trends  
- Highlighted regions with unstable rainfall patterns  
- Assessed climate stress through extreme weather frequency  
- Compared Ethiopia’s climate risk relative to neighboring countries  
- Provided evidence-based recommendation for climate finance prioritization  



## Next Steps
- Build interactive Streamlit dashboard for climate visualization  
- Improve vulnerability scoring using weighted climate indicators  
- Apply forecasting models for future climate trends  
- Extend analysis to additional African regions for broader comparison  