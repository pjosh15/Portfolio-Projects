# Portfolio-Projects
Project Objective
The goal of this project is to build an end-to-end data pipeline that identifies high-yield real estate markets across the US. By applying strict financial "Arbitrage" rules to historical Zillow data, the engine isolates metropolitan areas where rental income is high relative to property values and is currently showing strong year-over-year momentum.

🛠 Tech Stack
Python (Pandas): Multi-stage ETL pipeline for data normalization and financial feature engineering.

Power BI: Executive-facing dashboard for portfolio visualization and market comparison.

Google Colab: Cloud-based development environment for data processing.


Metric,Index Used,Methodology
Home Value,ZHVI,"Represents the ""typical"" home value (35th-65th percentile), removing luxury outliers."
Market Rent,ZORI,"Tracks the ""market-rate"" rent for repeat-units, ensuring a like-for-like comparison over time."
