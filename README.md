# Analyzing Historical Stock/Revenue Data and Building a Dashboard

This repository contains a Jupyter notebook that analyzes historical **stock prices** and **company revenue** for **Tesla (TSLA)** and **GameStop (GME)**, then builds an **interactive Plotly dashboard**. Stock prices are fetched with `yfinance`, and revenue tables are scraped from public HTML pages.

---

## Features

- **Data collection**
  - Stock history via [`yfinance`](https://pypi.org/project/yfinance/)
  - Revenue tables scraped with `pandas.read_html` (or `requests` + `BeautifulSoup`)
- **Visualization**
  - Plotly dashboard with two synchronized subplots: **Share Price** and **Revenue**
  - Reusable function `make_graph(stock_data, revenue_data, stock)`
- **Notebook-first workflow**
  - A single, runnable notebook with clear steps end-to-end

---

## Tech Stack

- Python 3.10+
- Jupyter Notebook / JupyterLab
- pandas, numpy
- plotly
- yfinance
- requests, beautifulsoup4 (optional; `pandas.read_html` may be enough)
