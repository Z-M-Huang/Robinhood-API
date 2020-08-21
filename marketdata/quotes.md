# /marketdata/quotes/

## Request GET Authorized:

Query Strings:

- bounds: trading
- include_inactive: true
- instruments: (comma deliminated urls for instruments, like: `https://api.robinhood.com/instruments/2fd39520-01a7-4612-ab1f-ddbb9a861268/,https://api.robinhood.com/instruments/29d287a3-771b-4414-95ed-8669423303bf/`)

## Response:

```json
{
  "results": [
    {
      "ask_price": "29.740000",
      "ask_size": 100,
      "bid_price": "29.510000",
      "bid_size": 1154,
      "last_trade_price": "29.760000",
      "last_extended_hours_trade_price": "29.510000",
      "previous_close": "28.140000",
      "adjusted_previous_close": "28.140000",
      "previous_close_date": "2020-08-19",
      "symbol": "LYFT",
      "trading_halted": false,
      "has_traded": true,
      "last_trade_price_source": "consolidated",
      "updated_at": "2020-08-21T10:33:47Z",
      "instrument": "https://api.robinhood.com/instruments/2fd39520-01a7-4612-ab1f-ddbb9a861268/"
    },
    {
      "ask_price": "31.370000",
      "ask_size": 393,
      "bid_price": "31.000000",
      "bid_size": 20,
      "last_trade_price": "31.410000",
      "last_extended_hours_trade_price": "31.310000",
      "previous_close": "29.420000",
      "adjusted_previous_close": "29.420000",
      "previous_close_date": "2020-08-19",
      "symbol": "UBER",
      "trading_halted": false,
      "has_traded": true,
      "last_trade_price_source": "consolidated",
      "updated_at": "2020-08-21T10:33:33Z",
      "instrument": "https://api.robinhood.com/instruments/29d287a3-771b-4414-95ed-8669423303bf/"
    }
  ]
}
```
