# Stock Data Scraper

This Go application scrapes stock data (company name, current price, and daily percentage change) for a list of companies from Yahoo Finance using the [Colly](https://github.com/gocolly/colly) web scraping framework. The results are saved into a `stocks.csv` file.

## Features

- Fetches live stock data from Yahoo Finance.
- Extracts company name, stock price, and percentage change.
- Saves data to a CSV file (`stocks.csv`).

## Prerequisites

- Go 1.18 or later installed
- Internet connection (to fetch data from Yahoo Finance)

## Installation

1. Clone the repository or copy the source files.
2. Navigate to the project directory.

```bash
go mod tidy
Usage
To run the scraper:

bash
Copy
Edit
go run main.go
This will:

Visit Yahoo Finance pages for a list of predefined stock tickers (e.g., MSFT, IBM, AAPL).

Scrape the company name, price, and change percentage.

Output the data to a stocks.csv file in the current directory.

Output
Example CSV format:

csv
Copy
Edit
company,price,change
Apple Inc.,173.69,+0.85%
Microsoft Corporation,312.12,-0.45%
...
Dependencies
Colly - Go library for web scraping

Notes
Be respectful of Yahoo Finance's terms of use and scraping limits.

Data accuracy depends on the structure of the Yahoo Finance webpage; changes in the site may break the scraper.

License
This project is licensed under the MIT License.

yaml
Copy
Edit

---

Would you like me to generate a `LICENSE` file or `Makefile` as well?
