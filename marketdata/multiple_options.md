# /marketdata/options/

## Request GET Authorized:

Query Strings:

- instruments: (comma deliminated urls for option instruments, like: `https://api.robinhood.com/options/instruments/473878af-9836-4295-a06f-85a92c9cf04f/,https://api.robinhood.com/options/instruments/7db4a2e6-5d31-4f24-8d44-b21327cf9ac8/`)

## Response:

```json
{
  "results": [
    {
      "adjusted_mark_price": "0.010000",
      "ask_price": "0.050000",
      "ask_size": 53,
      "bid_price": "0.000000",
      "bid_size": 0,
      "break_even_price": "7.510000",
      "high_price": "0.050000",
      "instrument": "https://api.robinhood.com/options/instruments/473878af-9836-4295-a06f-85a92c9cf04f/",
      "last_trade_price": "0.040000",
      "last_trade_size": 50,
      "low_price": "0.030000",
      "mark_price": "0.025000",
      "open_interest": 652,
      "previous_close_date": "2020-08-19",
      "previous_close_price": "0.010000",
      "volume": 105,
      "chance_of_profit_long": "0.061313",
      "chance_of_profit_short": "0.938687",
      "delta": "0.070945",
      "gamma": "0.419099",
      "implied_volatility": "0.883452",
      "rho": "0.000013",
      "theta": "-0.021958",
      "vega": "0.000497",
      "high_fill_rate_buy_price": "0.040000",
      "high_fill_rate_sell_price": "0.000000",
      "low_fill_rate_buy_price": "0.010000",
      "low_fill_rate_sell_price": "0.030000"
    },
    {
      "adjusted_mark_price": "0.010000",
      "ask_price": "0.050000",
      "ask_size": 51,
      "bid_price": "0.000000",
      "bid_size": 0,
      "break_even_price": "12.490000",
      "high_price": "0.050000",
      "instrument": "https://api.robinhood.com/options/instruments/7db4a2e6-5d31-4f24-8d44-b21327cf9ac8/",
      "last_trade_price": "0.020000",
      "last_trade_size": 1,
      "low_price": "0.010000",
      "mark_price": "0.025000",
      "open_interest": 1698,
      "previous_close_date": "2020-08-19",
      "previous_close_price": "0.010000",
      "volume": 42,
      "chance_of_profit_long": "0.014186",
      "chance_of_profit_short": "0.985814",
      "delta": "-0.009293",
      "gamma": "0.008234",
      "implied_volatility": "3.179728",
      "rho": "-0.000005",
      "theta": "-0.037943",
      "vega": "0.000239",
      "high_fill_rate_buy_price": "0.040000",
      "high_fill_rate_sell_price": "0.000000",
      "low_fill_rate_buy_price": "0.010000",
      "low_fill_rate_sell_price": "0.030000"
    }
  ]
}
```
