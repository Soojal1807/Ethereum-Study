# Ethereum Study & Analysis

This repository contains a Python script designed to fetch historical Ethereum (ETH-USD) data, perform various analyses, and generate a comprehensive report.

## Project Structure

- `Bitcoin study.py`: The main Python script that performs the data fetching, analysis, and report generation.
- `report.txt`: The generated report containing the analysis results.

## Features

- **Historical Data Extraction**: Fetches Ethereum historical price data (ETH-USD) using the `yfinance` library.
- **Volatility Index Calculation**: Calculates the annualized volatility index based on daily returns, providing insights into price stability.
- **Peak Time Identification**: Identifies the date when Ethereum reached its highest price.
- **Best Profit Date (Single-Day Gain)**: Determines the date with the largest single-day percentage price increase, indicating a potentially optimal short-term profit opportunity.
- **Bear & Bull Timeline Identification**: Analyzes price movements to identify periods of sustained downward (bear) and upward (bull) trends.
- **Comprehensive Reporting**: Generates a `report.txt` file summarizing all findings, including volatility interpretation and identified market trends.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Soojal1807/Ethereum-Study.git
    cd Ethereum-Study
    ```
2.  **Install dependencies:**
    This script requires `yfinance`, `pandas`, and `numpy`. You can install them using pip:
    ```bash
    pip install yfinance pandas numpy
    ```
3.  **Run the analysis script:**
    ```bash
    python "Bitcoin study.py"
    ```
    The script will fetch data, perform analysis, and generate `report.txt` in the same directory.

## Report Details

The `report.txt` includes:

- **Data Range**: The start and end dates of the analyzed historical data.
- **Peak Time**: The date and price of Ethereum's all-time high.
- **Best Single-Day Profit**: The date and percentage gain of the highest single-day price increase.
- **Volatility Index**: The annualized volatility value, accompanied by an interpretation (Low, Moderate, or High Volatility).
- **Bear Timelines**: Periods identified as bear markets based on consistent average daily price drops.
- **Bull Timelines**: Periods identified as bull markets based on consistent average daily price rises.

## Volatility Interpretation

- **Low Volatility (< 30%)**: Generally indicates less price fluctuation, often considered safer for stable investments.
- **Moderate Volatility (30% - 60%)**: Suggests some price fluctuation, presenting both opportunities for growth and inherent risk.
- **High Volatility (> 60%)**: Implies significant price fluctuation, associated with higher risk but also potential for higher returns.

## Disclaimer

This script is for educational and informational purposes only. It is not financial advice. Cryptocurrency markets are highly volatile, and past performance is not indicative of future results. Always conduct your own research and consult with a financial professional before making any investment decisions.

## License

[MIT License](LICENSE) 
