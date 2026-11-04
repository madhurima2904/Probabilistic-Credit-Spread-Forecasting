
| Task | Member | Action | Location |
|---|---|---|---|
| Data Collection | LIM Shihan | Pulled the monthly macro series (FEDFUNDS, UNRATE, CPIAUCSL, PALLFNFINDEXM, POILWTIUSDM) from the FRED API and downloaded the daily HYOAS series (`BAMLH0A0HYM2`) as a CSV. Saved the raw files unedited. | `DS603_Project.ipynb`, section [Data Collection]; `data/raw/` |
| Data cleaning and merging | Madhurima Subramaniam Rudra | Cleaned the daily HYOAS data, converted it to month-end values, and merged it with the monthly macro series | `DS603_Project.ipynb`, section [Data Cleaning] |
| Feature engineering | Madhurima Subramaniam Rudra | Built the 6-month target ($S_{t+6} - S_t$), 1-month spread change, and 1-month lags for FEDFUNDS, UNRATE, and CPI YoY | `DS603_Project.ipynb`, section [Feature engineering]; `data/processed/` |
| Exploratory data analysis | LIM Shihan | Explored the spread and macro series with trend plots and box plots, and examined the shape of the 6-month spread changes | `DS603_Project.ipynb`, section [EDA]; `output/EDA/` |
| Distribution fitting (Normal and Student-t) | LIM Shihan | Fitted Normal and Student-t distributions to monthly spread changes by MLE, and compared them using AIC and Q-Q plots | `DS603_Project.ipynb`, section [Distribution Fitting]; `output/figures/` |
| Monte Carlo simulation | Madhurima Subramaniam Rudra | Simulated six monthly changes from the fitted distribution and took the 5th and 95th percentiles as uncertainty bands | `DS603_Project.ipynb`, section [6 month simulation]; `output/figures` |
| Ridge regression | Madhurima Subramaniam Rudra | Fitted Ridge with time-series cross-validation and compared it to the no change benchmark | `DS603_Project.ipynb`, section [Model]; `output/figures` |
| Presentation slides | LIM Shihan | Designed and prepared the presentation slides summarising the project's methods, results and limitations | `output/presentation/` |
| Repository Structure | Madhurima Subramaniam Rudra | Formatted the repository with README, AI_USAGE, files. Generated and uploaded the necessary output figures, jupyter notebook. | `DS603_project` |
