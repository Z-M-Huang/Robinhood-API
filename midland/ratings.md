# /midlands/ratings/

## Request GET Authorized:

Query Strings:

- ids (comma delimited uuid strings, like `3d961844-d360-45fc-989b-f6fca761d511,76637d50-c702-4ed1-bcb5-5b0732a81f48`)

## Response:

```json
{
  "results": [
    {
      "ask_price": "11778.710000",
      "bid_price": "11758.758276",
      "mark_price": "11768.734138",
      "high_price": "11907.225000",
      "low_price": "11717.118760",
      "open_price": "11853.055000",
      "symbol": "BTCUSD",
      "id": "3d961844-d360-45fc-989b-f6fca761d511",
      "volume": "0.000000"
    },
    {
      "ask_price": "407.930000",
      "bid_price": "407.371140",
      "mark_price": "407.650570",
      "high_price": "417.860000",
      "low_price": "405.450000",
      "open_price": "415.325000",
      "symbol": "ETHUSD",
      "id": "76637d50-c702-4ed1-bcb5-5b0732a81f48",
      "volume": "0.000000"
    }
  ]
}
```
