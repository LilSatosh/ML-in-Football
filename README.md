# ML-in-Football
Code and datasets for the paper "Machine Learning in Football: A Comparative Analysis of Supervised and Unsupervised Techniques". Compares Logistic Regression/SVM/Decision Trees against PCA/K-Means Clustering to discover tactical player roles in the 2024/25 European Top 5 Leagues.
Code and datasets for the paper "Machine Learning in Football: A Comparative Analysis of Supervised and Unsupervised Techniques". Compares Logistic Regression/SVM/Decision Trees against PCA/K-Means Clustering to discover tactical player roles in the 2024/25 European Top 5 Leagues.

# Machine Learning in Football: Player Profiling (2024/25)
This repository contains the source code, datasets, and results for the research paper: "Machine Learning in Football: A Comparative Analysis of Supervised and Unsupervised Techniques for Player Profiling."
# Project Overview
Traditional football positions (Defender, Midfielder, Forward) often fail to capture the nuance of modern hybrid roles. This project uses data from the 2024/25 season (Top 5 European Leagues) to:
1.  Test Traditional Labels: Using Supervised Learning (Logistic Regression, SVM, Decision Trees).
2.  Discover New Roles: Using Unsupervised Learning (PCA + K-Means Clustering).
#Key Findings
While Supervised models struggled to classify hybrid players (Accuracy ~88%), the Unsupervised K-Means model identified 5 distinct tactical profiles based on performance metrics:
 The Elite Center back: Pure defensive volume (Clearances/Blocks).
 The Goal Poacher: High Goals/xG, low build-up contribution.
 The Elite Creator: High Progressive Carries and Assists.
 The Deep-Lying Playmaker: High Progressive Passes from deep areas.
 The Ball-Winning Midfielder: High Tackles/Interceptions ("The Engine Room").
#Repository Structure
 ` ML_in_Football-Football_Clustering.ipynb` - The main Jupyter Notebook containing all code (Data cleaning, Models, and Results).
 ` fbref_big5_stats_24_25.csv` - The raw standard stats dataset sourced from FBref.
` fbref_big5_stats_24_25_def.csv` - The raw defense stats dataset sourced from FBref.
 `README.md` - Project documentation.
#Dependencies
To run this notebook, you will need Python 3.x and the following libraries:
pip install pandas numpy scikit-learn matplotlib seaborn

link to standard stats dataset: https://fbref.com/en/comps/Big5/2024-2025/stats/players/2024-2025-Big-5-European-Leagues-Stats
link to defence stats dataset: https://fbref.com/en/comps/Big5/2024-2025/defense/players/2024-2025-Big-5-European-Leagues-Stats
