# /marketdata/options/:uuid

## Request GET Authorized:

Path Parameters:

- uuid (like `473878af-9836-4295-a06f-85a92c9cf04f`)

## Response:

```json
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
}
```
