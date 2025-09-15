\# U.S. Business Formation Statistics Project



\## Motivation

The U.S. Census Bureau publishes monthly Business Formation Statistics (BFS) to track new business applications.  

This project explores the data, identifies key patterns, and builds a machine learning model (XGBoost) to forecast future business applications.



\## Files in this Repository

\- `notebook.ipynb` – Jupyter Notebook with analysis, feature engineering, modeling, and forecasting.

\- `bfs\_monthly.csv` – Dataset (source: U.S. Census Bureau).

\- `README.md` – Project description and results.



\## Libraries Used

\- pandas  

\- matplotlib, seaborn  

\- numpy  

\- xgboost  

\- scikit-learn  



\## Key Findings

\- Business applications were stable until ~2020, then surged during the COVID-19 pandemic.  

\- The distribution is bimodal: pre-pandemic vs. post-pandemic levels.  

\- XGBoost captures overall trends but struggles with sudden volatility.  

\- Forecast suggests applications remain elevated in the coming year.  



\## Acknowledgments

\- Dataset: \[U.S. Census Bureau – Business Formation Statistics](https://www.census.gov/econ/bfs/index.html)



