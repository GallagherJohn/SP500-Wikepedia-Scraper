# SP500-Wikepedia-Scraper
Program to parse the HTML of the S&amp;P500 Wikepedia page and return a list of every stock symbol that is in the S&amp;P500.

This program makes a request to a Wikipedia page that contains the list of S&P500 stocks, parses the HTML of the page to extract the list of stock symbols, and returns the list of symbols.

Note that this approach is prone to break if the format of the Wikipedia page changes, so it's generally a good idea to use a more reliable source for getting the list of S&P500 symbols. One option could be to use a paid financial data API such as the IEX Cloud API.
