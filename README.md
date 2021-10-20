# Usage

This repository contains the OpenApi generator(s), if you only want to use the client libraries, please follow one of
the links bellow

## Client Libraries

- [Python Client](https://github.com/GoPlan-Finance/eodhistoricaldata-openapi-python)
- [Javascript / Typescript Client](https://github.com/GoPlan-Finance/eodhistoricaldata-openapi-javascript)

If your favorite language is not listed above, feel free to open an Issue or submit a PR !

## Re-generating libraries

```bash
# You need Java JRE installed before running this
npm run generate
```

# Status

- ✅ Fully implemented
- 🟨 Partially implemented
- ⏳ Will be implemented soon

If the endpoint is not yet implemented, and dont have a ⏳, feel free to submit a PR, otherwise please check with us before to make sure we dont duplicate work.

### Historical Prices, Splits and Dividends Data API

- ✅ Stock Price Data API (End-Of-Day Historical Data)
- ✅ Live (Delayed) Stock Prices API
- ⏳ Historical Splits, Dividends and Short Interest API
- ⏳ Technical Indicator API
- ⏳ Intraday Historical Data API
- Options Data API

### Fundamental and Economic Financial Data API

- Insider Transactions API
- ✅ Fundamental Data: Stocks, ETFs, Mutual Funds, Indices
   - ✅ General
   - ✅ Highlights
   - ✅ Valuation
   - ✅ SharesStats
   - ✅ Technicals
   - ✅ SplitsDividends
      - NumberDividendsByYear
   - ✅ AnalystRatings
   - ✅ Holders
      - Institutions
      - Funds
   - ✅ InsiderTransactions
   - ✅ ESGScores
   - ✅ outstandingShares
   - ✅ Earnings
      - History
      - Trend
      - Annual
   - ✅ Financials
      - Balance_Sheet
      - Cash_Flow
      - Income_Statement


- ⏳ Calendar. Upcoming Earnings, Trends, IPOs and Splits
- Macroeconomics Data and Macro Indicators API
- Economic Data API
- Bonds Fundamentals and Historical API

### Exchanges (Stock Market) Financial APIs

- ⏳ Bulk API for EOD, Splits and Dividends
- ✅ Exchanges API. Get List of Tickers
   - ✅ Get List of Exchanges
   - ✅ Get List of Tickers (Exchange Symbols)
- ⏳ Exchanges API. Trading Hours and Market Holidays
   - ⏳ Get Exchange Details and Trading Hours
   - ⏳ Market Holidays Data API
- ⏳ Financial News API
- Stock Market Screener API
- ✅ Search API for Stocks, ETFs, Mutual Funds and Indices

### Available Data Feeds

- List of Supported Exchanges
- List of Supported CRYPTO Currencies
- List of Supported Futures/Commodities
- List of Supported Forex Currencies
- List of Supported Indices

### User API

- User API
