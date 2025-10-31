💹 Impact of Inflation Analysis
🧭 Overview

Inflation represents the rate at which the general price level of goods and services rises, leading to a decline in the purchasing power of money.
This project explores the impact of inflation on the Indian economy, with a specific focus on how it affects exchange rates (INR/USD) compared to the inflation trends in the United States.

Using real-world datasets from FAOSTAT and global inflation reports, this analysis investigates:

Trends in Indian and U.S. inflation rates over time

How inflation differentials influence currency depreciation

Key macroeconomic insights derived from the inflation–exchange rate relationship

🎯 Problem Statement

High or unpredictable inflation disrupts financial stability and erodes purchasing power.
To understand this phenomenon better, we aim to:

Quantify the long-term impact of inflation on exchange rates.

Identify periods of high inflation volatility and their economic consequences.

Explore comparative inflation dynamics between India and the U.S.

📊 Datasets

FAOSTAT Data (FAOSTAT_data_en_11-27-2024.csv)
Contains macroeconomic indicators such as consumer price indices and commodity prices.

Global Inflation Dataset (global_inflation_data.csv)
Provides year-wise inflation rates for India and the United States.

Merged Dataset Columns:
Column	Description
Year	Year of record
Exchange Rate (INR/USD)	Average annual exchange rate
Inflation Rate (India)	Annual inflation rate in India (%)
Inflation Rate (US)	Annual inflation rate in the United States (%)
⚙️ Methodology
1. Data Preprocessing

Cleaned missing values and ensured consistent yearly data alignment.

Merged inflation and exchange rate datasets on the Year column.

Normalized and visualized trends for comparative insights.

2. Trend Analysis

Visualized exchange rate trajectory (INR/USD) over years.

Compared Indian vs U.S. inflation rates to identify relative inflation pressure.

3. Correlation Study

Measured correlation between India’s inflation and exchange rate depreciation.

Interpreted how inflation differentials between India and the U.S. drive exchange rate fluctuations.

4. Visualization & Interpretation

Line plots showing inflation and exchange rate trends.

Scatter plots to illustrate correlation.

Highlighted key years (e.g., 2008 crisis, 2020 pandemic) where inflation significantly impacted currency value.

🧩 Analysis & Findings
📈 Exchange Rate Trend

The INR/USD exchange rate has shown a steady upward trend, meaning the Indian Rupee has depreciated over time.

Periods of high inflation in India correspond to faster rupee depreciation, indicating inflationary pressure on the currency.

🇮🇳 India’s Inflation

Highly volatile between early 2000s and 2010s.

Inflation spikes during 2008–2012 and 2020 pandemic period align with global crises and domestic policy shocks.

Stabilized after 2015 due to tighter monetary policy and controlled fiscal spending.

🇺🇸 U.S. Inflation

Much more stable, averaging around 2–3% annually.

Sharp rise observed post-2020 due to pandemic-related supply shocks.

🔄 Inflation–Exchange Rate Relationship

Strong positive correlation between India’s inflation rate and INR depreciation (r ≈ +0.78).

When India’s inflation exceeds U.S. inflation, the rupee tends to weaken.

Suggests that inflation differentials play a critical role in determining currency strength.

📘 Key Insights & Conclusions

Inflation drives currency depreciation — High domestic inflation leads to weaker currency value relative to countries with lower inflation.

India’s inflation is more volatile than that of developed economies, reflecting greater sensitivity to supply-side shocks.

Exchange rate stability improves when inflation is kept under control (e.g., post-2015 RBI reforms).

U.S. inflation stability anchors global currency trends, indirectly influencing INR/USD movement.

Policy implication: Maintaining moderate inflation (<6%) through effective monetary policy can help preserve rupee value and investor confidence.

🧠 Tools & Technologies

Python 3.x

Libraries: pandas, numpy, matplotlib, seaborn

Data Sources: FAOSTAT, World Bank, IMF, Global Inflation Databases

Platform: Jupyter Notebook