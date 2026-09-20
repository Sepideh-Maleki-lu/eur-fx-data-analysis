# EUR Foreign Exchange Data Analysis

This project was completed as part of the **Data Analysis with Python**
training at the Digital Learning Hub Luxembourg.

The objective of the project is to investigate the claim:

> "The euro has weakened against other major currencies since it launched."

The analysis focuses on the EUR/USD and EUR/CHF exchange rates using
historical data from the European Central Bank (ECB).

## Data

- Source: European Central Bank (ECB) euro reference rates
- Period: January 1999 – September 2026
- Main currencies analyzed: USD and CHF
- Frequency: Daily exchange-rate observations

## Analysis

The project includes:

- Importing and inspecting the dataset
- Converting and cleaning date information
- Checking and handling missing values
- Sorting time-series data correctly
- Calculating daily exchange-rate changes
- Computing yearly average exchange rates
- Comparing exchange-rate changes from different starting years
- Indexing EUR/USD and EUR/CHF to a common base of 100
- Measuring correlation between daily movements
- Analyzing volatility over time
- Creating financial data visualizations

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Main Findings

The analysis shows different long-term behavior for the two exchange rates.

EUR/CHF experienced a clear long-term decline, with the euro losing around
41% of its value against the Swiss franc over the full period.

EUR/USD showed a much smaller decline over the full period, and the result
depends strongly on the chosen starting year.

The analysis therefore highlights that statements such as "the euro has
weakened" should specify both the comparison currency and the time period.

## Files

- `DA_EUR_FX_SEPIDEH_MALEKI.ipynb` – Python analysis and visualizations
- `DA_EUR_FX_Report_Sepideh Maleki.pdf` – Project report

## Author

Sepideh Maleki-Roudposhti

Master in Financial Mathematics  
University of Luxembourg
