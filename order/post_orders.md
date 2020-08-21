# /orders/

## Request POST Authorized:

```json
{
  "ref_id": "9540ac01-b118-4765-8558-7e5ac186111a",
  "account": "https://api.robinhood.com/accounts/123456789/",
  "instrument": "https://api.robinhood.com/instruments/61fec2c4-2c8e-470d-88b1-6e211f004d1e/",
  "symbol": "IDEX",
  "quantity": "1",
  "side": "buy",
  "type": "market",
  "trigger": "immediate",
  "time_in_force": "gfd",
  "extended_hours": false,
  "price": "1.47"
}
```

## Response:

Status: 201
