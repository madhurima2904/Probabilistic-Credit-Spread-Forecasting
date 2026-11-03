
| Task | Member | Action | Location |
|---|---|---|---|
| Data Collection| LIM Shihan | | `DS603_Project.ipynb`, section [X]; `data/raw/` |
| Data cleaning and merging | Madhurima Subramaniam Rudra | Cleaned the daily HYOAS data, converted it to month-end values, and merged it with the monthly macro series | `DS603_Project.ipynb`, section [Data Cleaning] |
| Feature engineering | Madhurima Subramaniam Rudra | Built the 6-month target ($S_{t+6} - S_t$), 1-month spread change, and 1-month lags for FEDFUNDS, UNRATE, and CPI YoY | `DS603_Project.ipynb`, section [Feature engineering]; `data/processed/` |
| [Task] | LIM Shihan | [Action] | [Location] |
| [Task] | LIM Shihan | [Action] | [Location] |
| Monte Carlo simulation | Madhurima Subramaniam Rudra | Simulated six monthly changes from the fitted distribution and took the 5th and 95th percentiles as uncertainty bands | `DS603_Project.ipynb`, section [6 month simulation]; `output/figures` |
| Ridge regression | Madhurima Subramaniam Rudra | Fitted Ridge with time-series cross-validation and compared it to the no change benchmark | `DS603_Project.ipynb`, section [Model]; `output/figures` |
| Presentation slides | LIM Shihan | [Action] | [Location] |
| Repository Structure | Madhurima Subramaniam Rudra | Formatted the repository with README, AI_USAGE, files. Generated and uploaded the necessary output figures, jupyter notebook. | `DS603_project` |
