# Scraping Morningstar Valuation Page
This repository contains a Jupyter notebook that scrapes the valuation page of a given stock on the Morningstar website and extracts the valuation ratios for the stock (which is up to 10 years of data).

## Installation
Clone the repository or download the zip file.
Make sure you have Python 3 and the required packages installed. You can install the required packages by running the following command in your terminal:

`pip install requests selenium pandas`

Make sure you have a web driver for your preferred browser installed. You can download the driver from the following links:

- Chrome: https://sites.google.com/chromium.org/driver/
- Firefox: https://github.com/mozilla/geckodriver/releases

Set the path to your web driver in the file.

## Usage
Open the Jupyter notebook in a vscode or any other IDE.
Replace the STOCK_TICKER variable with the ticker symbol of the stock you want to scrape and run the Jupyter notebook.

There are several metrics/ratios that this Jupyter notebook will return:
- **Price/Sales**: calculated by taking a company's market capitalization (the number of outstanding shares multiplied by the share price) and divide it by the company's total sales or revenue over the past 12 months.
- **Price/Earnings**: the ratio for valuing a company that measures its current share price relative to its earnings per share (EPS).
- **Price/Cash Flow**: is a stock valuation indicator or multiple that measures the value of a stock's price relative to its operating cash flow per share.
- **Price/Book**: is the ratio of the market value of a company's shares (share price) over its book value of equity. The book value of equity, in turn, is the value of a company's assets expressed on the balance sheet.
- **Price/Foward Earnings**: is a version of the ratio of price-to-earnings (P/E) that uses forecasted earnings for the P/E calculation. While the earnings used in this formula are just an estimate and not as reliable as current or historical earnings data, there are still benefits to estimated P/E analysis.
- **PEG Ratio**: is a valuation metric for determining the relative trade-off between the price of a stock, the earnings generated per share (EPS), and the company's expected growth.

## Contributing
This Jupyter notebook is for educational use only. Contributions are welcome! If you find any issues or have any suggestions, please create an issue or a pull request.

## License
This project is licensed under the MIT License.
