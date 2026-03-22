# Awesome SEC Filings [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, data sources, libraries, and resources for working with SEC filings (13F, 10-K, 10-Q, 8-K, and more).

Whether you're tracking institutional investors through 13F filings, analyzing earnings reports, or building financial data pipelines — this list has you covered.

## Contents

- [Platforms & Data Sources](#platforms--data-sources)
- [Libraries & Tools](#libraries--tools)
- [APIs](#apis)
- [Datasets](#datasets)
- [Tutorials & Articles](#tutorials--articles)
- [Communities](#communities)

## Platforms & Data Sources

### 13F / Institutional Holdings

- [13F Insight](https://13finsight.com/) - Track institutional investor 13F holdings with AI-powered analysis, position change alerts, and filing summaries.
- [WhaleWisdom](https://whalewisdom.com/) - 13F filing tracker with historical data, top holders, and portfolio analytics.
- [Fintel](https://fintel.io/) - Institutional ownership data, insider trading, short interest, and 13F filings.
- [Whaletrace](https://www.whaletrace.com/) - Visual 13F filing tracker for following hedge fund portfolios.
- [HoldingsChannel](https://www.holdingschannel.com/) - Top institutional holders and 13F analysis.

### General SEC Filings

- [SEC EDGAR](https://www.sec.gov/edgar/searchedgar/companysearch) - The official SEC filing system. Free access to all public filings.
- [EDGAR Full-Text Search](https://efts.sec.gov/LATEST/search-index?q=%22machine+learning%22) - Full-text search across all EDGAR filings.
- [Last10K](https://last10k.com/) - AI-generated summaries of 10-K and 10-Q filings in plain English.
- [Docoh](https://docoh.com/) - SEC filings with AI-powered analysis and company insights.
- [Bamsec](https://www.bamsec.com/) - Fast, clean SEC filing viewer.
- [OpenInsider](http://openinsider.com/) - Real-time insider trading data from SEC Form 4 filings.
- [TradeInsight.info](https://tradeinsight.info) - Timely notification service for SEC Form 4 filling + Politician Trade Insight.

## Libraries & Tools

### Python

- [edgartools](https://github.com/dgunning/edgartools) - A Python library for navigating SEC EDGAR with a clean, Pythonic interface. Supports all filing types.
- [sec-parser](https://github.com/alphanome-ai/sec-parser) - A robust SEC EDGAR filing parser for extracting structured data from 10-Q, 10-K filings.
- [python-edgar](https://github.com/edouardswiac/python-edgar) - Download the SEC EDGAR company filing index and parse XBRL data.
- [sec-api](https://github.com/sec-api/sec-api-python) - Python client for SEC-API.io to query and download SEC filings.
- [SEC-Edgar-Downloader](https://github.com/jadchaar/sec-edgar-downloader) - Download SEC filings from EDGAR by ticker or CIK.
- [py-sec-edgar](https://github.com/ryansmccoy/py-sec-edgar) - Tools for working with SEC EDGAR data in Python.
- [secedgar](https://github.com/sec-edgar/sec-edgar) - SEC EDGAR filings downloader and parser.

### R

- [edgarWebR](https://github.com/mwaldstein/edgarWebR) - R package for accessing SEC EDGAR filings data.
- [finreportr](https://github.com/sewardlee337/finreportr) - Download and parse SEC financial reports in R.

### JavaScript / TypeScript

- [sec-edgar-api](https://github.com/janlukasschroeder/sec-edgar-api) - Node.js client for SEC EDGAR API.

### Command Line

- [edgar-tool](https://github.com/bellingcat/edgar-tool) - CLI tool from Bellingcat for searching and downloading SEC EDGAR filings.

## APIs

- [SEC EDGAR API](https://www.sec.gov/edgar/sec-api-documentation) - Official SEC EDGAR RESTful API. Free, no API key required. Rate limited to 10 req/sec.
- [SEC-API.io](https://sec-api.io/) - Commercial API for real-time SEC filing search, download, and XBRL-to-JSON conversion.
- [Financial Modeling Prep](https://financialmodelingprep.com/) - SEC filings, financial statements, and institutional holdings API.
- [Polygon.io](https://polygon.io/) - Market data API with SEC filings and reference data.

## Datasets

- [SEC EDGAR Full Index](https://www.sec.gov/Archives/edgar/full-index/) - Complete EDGAR filing index, updated quarterly.
- [SEC Financial Statement Datasets](https://www.sec.gov/dera/data/financial-statement-data-sets) - Structured financial statement data extracted from XBRL filings.
- [SEC 13F Data (Kaggle)](https://www.kaggle.com/datasets/loisjones/13f-data) - Historical 13F filing data on Kaggle.

## Tutorials & Articles

- [SEC EDGAR Beginner's Guide](https://www.sec.gov/oiea/Article/edgarguide.html) - Official SEC guide to using EDGAR.
- [Analyzing 13F Filings with Python](https://blog.quant-quest.com/analyzing-13f-filings/) - Tutorial on parsing and analyzing 13F data programmatically.
- [Understanding Institutional 13F Filings](https://www.investopedia.com/terms/1/13f.asp) - Investopedia explainer on 13F filings.

## Communities

- [r/SecurityAnalysis](https://www.reddit.com/r/SecurityAnalysis/) - Reddit community for fundamental analysis and SEC filing discussion.
- [r/investing](https://www.reddit.com/r/investing/) - General investing discussion.
- [Quantocracy](https://quantocracy.com/) - Aggregator for quantitative finance blog posts.

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
