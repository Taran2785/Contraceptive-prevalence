Contraceptive Usage Prevalence Analysis

Overview

This project analyzes the prevalence of contraceptive usage among all women, married women, and sexually active unmarried women aged 15 to 49 worldwide from 1960 to 2023. The dataset underwent missing data analysis, and missing values were handled using KNN imputation.

Dataset available at World Bank Open Data

The dataset contains:

Countries: Various nations worldwide.

Years: 1960 to 2023.

Prevalence Rates: Contraceptive prevalence for different groups of women.

Key Tasks

Missing Data Analysis:

Conducted Little's MCAR test to determine if data was MCAR (Missing Completely at Random), MAR (Missing at Random), or MNAR (Missing Not at Random).

Identified missing data patterns using percentage analysis for each country and year.

Data Preprocessing:

Converted dataset from wide format to long format for easier analysis.

Cleaned column names by extracting valid year values.

Ensured categorical and numeric data types were correctly assigned.

Imputation Using KNN:

Used K-Nearest Neighbors (KNN) Imputation to fill missing values.

Chose an optimal k value based on performance.

Ensured imputed data maintained statistical properties.

Exploratory Data Analysis (EDA):

Visualized contraceptive prevalence trends over time.

Compared prevalence rates across different groups.

Time Series Analysis

Potential application of ARIMA or Prophet for future contraceptive trends.

Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)

KNN Imputation (from sklearn.impute.KNNImputer)

Statsmodels (for missing data analysis)

How to Use


Install dependencies:

pip install pandas numpy scikit-learn statsmodels matplotlib seaborn

Run the preprocessing and imputation script:

python preprocess_and_impute.py

Analyze results and visualizations.

Results

Identified that missing data is not MCAR, indicating systematic patterns in missingness.

Applied KNN imputation, which improved data completeness while preserving trends.

Prepared data for further forecasting and predictive modeling.

Future Enhancements

Implement ARIMA or Prophet for time series forecasting.

Explore regional differences in contraceptive usage trends.

Develop an interactive dashboard for better visualization.

Contributors

[Taranjit Kaur]

Data Analysis & Preprocessing

KNN Imputation & Visualization

