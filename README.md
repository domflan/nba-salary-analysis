# 🏀 NBA Salary Analysis: Advanced vs. Traditional Stats and Player Salaries (2019–2023)

This project explores the relationship between NBA player performance metrics and salary data from 2019 to 2023. Using both traditional stats (e.g., points, assists, rebounds) and advanced metrics (e.g., offensive win shares, defensive win shares, true shooting percentage), we analyzed how well these factors predict player compensation across different positions.

## 📊 Key Questions
- Which performance metrics correlate most with player salary across positions?
- Are players with high efficiency metrics better compensated?
- Do advanced stats offer better salary prediction than traditional stats?

## 📁 Data Sources
- **Player Stats:** Kaggle NBA player metrics dataset
- **Salaries:** Scraped from Hoopshype using BeautifulSoup

## 🛠️ Tools & Methods
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Web scraping with BeautifulSoup
- Data aggregation and cleaning
- Regression modeling and correlation analysis

## 📈 Key Insights
- Traditional stats (PTS, REB, AST) are much stronger predictors of salary than advanced stats
- Efficiency metrics (OWS, DWS, TS%) do show salary trends — especially for Point Guards and Centers — but add little to prediction models beyond traditional stats
- Regression models confirm traditional metrics predict salaries best (R² = 0.54)

## 📎 Files Included
- `ProjectScraping.ipynb` – Web scraping salary data
- `CombinedStats.ipynb` – Cleaning & merging datasets
- `merged_player_stats_salaries.csv` – Final dataset
- `NBA Advanced-TraditionalStatsVsSalary.pdf` – Final report

## 📄 Report
[📥 View Full Report (PDF)](https://github.com/domflan/domflan/raw/main/NBA%20Advanced-TraditionalStatsVsSalary.pdf)
