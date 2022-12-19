# Node-js-Portfolio

This program reads the transactions from the CSV file using the csv-parser library, calculates the portfolio value by adding deposits and subtracting withdrawals, and filters the portfolio value by token if a token is specified. It also uses the Cryptocompare API to get the exchange rates for the various tokens.

To run this program, you can use the following command:

 node main.js [token] [date]
If no token or date is specified, the latest portfolio value for all tokens will be displayed. If a token is specified, the latest portfolio value for that token will be displayed. If a date is specified, the portfolio value for all tokens at that date will be displayed. If both a token and a date are specified, the portfolio value for that token at that date will be displayed.
