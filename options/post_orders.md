# /options/orders/

## Request POST Authorized:

```json
{
  "quantity": "1",
  "direction": "debit",
  "price": "0.4",
  "type": "limit",
  "account": "https://api.robinhood.com/accounts/123456789/",
  "time_in_force": "gfd",
  "trigger": "immediate",
  "legs": [
    {
      "side": "buy",
      "option": "https://api.robinhood.com/options/instruments/8a8775d0-9377-4d8d-88de-4f6f2dcc025c/",
      "position_effect": "open",
      "ratio_quantity": "1"
    }
  ],
  "override_day_trade_checks": false,
  "override_dtbp_checks": false,
  "ref_id": "3e71ed78-e7cc-4d29-948a-a2ac69166e0c"
}
```

## Response:

```json
{
  "cancel_url": "https://api.robinhood.com/options/orders/c3a87025-d186-4d13-896a-dd644315790c/cancel/",
  "canceled_quantity": "0.00000",
  "created_at": "2020-08-21T11:16:02.197284Z",
  "direction": "debit",
  "id": "c3a87025-d186-4d13-896a-dd644315790c",
  "legs": [
    {
      "executions": [],
      "id": "46651403-b614-4792-93a2-8bbe109b3993",
      "option": "https://api.robinhood.com/options/instruments/8a8775d0-9377-4d8d-88de-4f6f2dcc025c/",
      "position_effect": "open",
      "ratio_quantity": 1,
      "side": "buy"
    }
  ],
  "pending_quantity": "1.00000",
  "premium": "40.00000000",
  "processed_premium": "0.0000",
  "price": "0.40000000",
  "processed_quantity": "0.00000",
  "quantity": "1.00000",
  "ref_id": "3e71ed78-e7cc-4d29-948a-a2ac69166e0c",
  "state": "unconfirmed",
  "time_in_force": "gfd",
  "trigger": "immediate",
  "type": "limit",
  "updated_at": "2020-08-21T11:16:02.197306Z",
  "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
  "chain_symbol": "PAYS",
  "response_category": null,
  "opening_strategy": "long_call",
  "closing_strategy": null,
  "stop_price": null
}
```
