# Stock-Dashboard
“Tesla & GameStop Stock Price and Revenue Analysis Dashboard”
# Stock Performance and Revenue Analysis Dashboard

## Project Overview
This project analyzes the **historical stock prices and quarterly revenue** of **Tesla (TSLA)** and **GameStop (GME)**. The goal is to visualize the relationship between stock performance and company revenue over time using **interactive Plotly graphs**.

---

## Dataset

### 1. Stock Data
- Source: [Yahoo Finance](https://finance.yahoo.com/)
- Method: Extracted using the `yfinance` Python library.
- Coverage:
  - **Tesla (TSLA):** From IPO (June 2010) to present.
  - **GameStop (GME):** From earliest available date to present.
- Columns: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Dividends`, `Stock Splits`

### 2. Revenue Data
- Source: Web scraping from lab-provided HTML pages.
- Method: Extracted using `BeautifulSoup` and stored in Pandas DataFrames.
- Columns: `Date`, `Revenue` (in millions USD)
- Coverage: Tesla and GameStop quarterly revenue data (filtered to June 2021 for graphs)

---

## Key Features
- Interactive visualization of **stock price vs revenue** for Tesla and GameStop.
- Historical stock data filtered to **June 2021** for consistent comparison.
- Revenue cleaned and numeric values ensured (no `$` or commas).
- Dashboard created using the `make_graph` function with Plotly subplots.

---

## Prerequisites
Ensure the following Python libraries are installed:

```bash
pip install yfinance
pip install pandas
pip install requests
pip install beautifulsoup4
pip install plotly
How to Run the Project
Clone or download this repository.

Open the Jupyter Notebook stock_analysis.ipynb.

Run each cell in order:
