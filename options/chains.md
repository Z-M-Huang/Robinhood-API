# /options/chains/

## Request GET Authorized:

Query Strings:

- ids (comma delimited uuid strings, like `3f631d1d-d432-4da6-84e1-f00495e853e8,baa3389f-0d44-445d-8c6c-065dbeb88f53`)

## Response:

```json
{
  "next": null,
  "previous": null,
  "results": [
    {
      "id": "baa3389f-0d44-445d-8c6c-065dbeb88f53",
      "symbol": "GRWG",
      "can_open_position": true,
      "cash_component": null,
      "expiration_dates": [
        "2020-09-18",
        "2020-10-16",
        "2021-01-15",
        "2021-04-16"
      ],
      "trade_value_multiplier": "100.0000",
      "underlying_instruments": [
        {
          "id": "a3c5c772-4e8d-45db-81f7-cd07ef03ff5e",
          "instrument": "https://api.robinhood.com/instruments/4ff99bec-58e1-4ee4-bc52-b12082707783/",
          "quantity": 100
        }
      ],
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      }
    },
    {
      "id": "74a446d6-7e8b-40de-957e-368f7a9b19a7",
      "symbol": "UBER",
      "can_open_position": true,
      "cash_component": null,
      "expiration_dates": [
        "2020-08-28",
        "2020-09-04",
        "2020-09-11",
        "2020-09-18",
        "2020-09-25",
        "2020-10-02",
        "2020-10-16",
        "2020-11-20",
        "2020-12-18",
        "2021-01-15",
        "2021-03-19",
        "2021-06-18",
        "2022-01-21"
      ],
      "trade_value_multiplier": "100.0000",
      "underlying_instruments": [
        {
          "id": "60863894-a675-48fb-992b-09a0d3c9939c",
          "instrument": "https://api.robinhood.com/instruments/29d287a3-771b-4414-95ed-8669423303bf/",
          "quantity": 100
        }
      ],
      "min_ticks": {
        "above_tick": "0.05",
        "below_tick": "0.01",
        "cutoff_price": "3.00"
      }
    }
  ]
}
```
