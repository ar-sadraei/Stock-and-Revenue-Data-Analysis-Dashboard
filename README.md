# Stock and Revenue Data Analysis Dashboard

## Project Overview
This project was developed as part of the **IBM Data Science Professional Certificate**. The goal is to analyze the financial performance of two major companies, **Tesla (TSLA)** and **GameStop (GME)**, by comparing their historical stock prices with their annual revenue data.

The project demonstrates the end-to-end data science workflow: data collection via APIs, web scraping, data cleaning using Pandas, and interactive visualization.

## Key Features
- **Stock Data Extraction:** Utilized the `yfinance` library to download historical stock prices.
- **Web Scraping:** Used `BeautifulSoup` and `requests` to scrape historical revenue data from Macrotrends.
- **Data Cleaning:** Processed raw HTML tables and JSON data into clean, analysis-ready Pandas DataFrames.
- **Visualization:** Developed a custom `make_graph` function using `Plotly` to generate a side-by-side dashboard of Share Price vs. Revenue.

## Project Files
- `Final Assignment Webscraping.ipynb`: The main notebook containing the final analysis and results.
- `Revenue Data and Building a Dashboard-v1.ipynb`: Detailed steps for creating the visualization dashboard.
- `WebScraping_Review_Lab.ipynb`: Preparatory lab exercises for mastering BeautifulSoup techniques.

## Installation & Setup
To run these notebooks locally, you will need Python installed along with the following libraries:

```bash
pip install yfinance pandas requests bs4 plotly
