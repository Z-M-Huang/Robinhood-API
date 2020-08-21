# /orders/

## Request GET Authorized:

## Response:

```json
{
  "next": "https://api.robinhood.com/orders/?cursor=4aXgk8u72iXpmsyoL4nzpi2Xr5f4iXFtwB4d3te5cTzrshU6bzaxVMU9",
  "previous": null,
  "results": [
    {
      "id": "845e0a73-a84f-4212-b3f1-c58e45d4ca5a",
      "ref_id": "c25caa22-5c72-415e-84ee-7e9ed85a21e4",
      "url": "https://api.robinhood.com/orders/845e0a73-a84f-4212-b3f1-c58e45d4ca5a/",
      "account": "https://api.robinhood.com/accounts/123456789/",
      "position": "https://api.robinhood.com/positions/123456789/b82eb909-7995-412f-8ddd-ce8d8d6bd391/",
      "cancel": null,
      "instrument": "https://api.robinhood.com/instruments/b82eb909-7995-412f-8ddd-ce8d8d6bd391/",
      "cumulative_quantity": "1.00000000",
      "average_price": "1496.55000000",
      "fees": "0.04",
      "state": "filled",
      "type": "market",
      "side": "sell",
      "time_in_force": "gfd",
      "trigger": "immediate",
      "price": "1421.42000000",
      "stop_price": null,
      "quantity": "1.00000000",
      "reject_reason": null,
      "created_at": "2019-01-23T04:05:06.789012Z",
      "updated_at": "2019-01-23T04:05:06.789012Z",
      "last_transaction_at": "2019-01-23T04:05:06.789012Z",
      "executions": [
        {
          "price": "1496.55000000",
          "quantity": "1.00000000",
          "settlement_date": "2020-08-11",
          "timestamp": "2019-01-23T04:05:06.789012Z",
          "id": "ceb9a6f6-1729-459b-baa6-e437104f77bb"
        }
      ],
      "extended_hours": true,
      "override_dtbp_checks": false,
      "override_day_trade_checks": false,
      "response_category": null,
      "stop_triggered_at": null,
      "last_trail_price": null,
      "last_trail_price_updated_at": null,
      "dollar_based_amount": null,
      "total_notional": {
        "amount": "1421.42",
        "currency_code": "USD",
        "currency_id": "1072fc76-1862-41ab-82c2-485837590762"
      },
      "executed_notional": {
        "amount": "1496.55",
        "currency_code": "USD",
        "currency_id": "1072fc76-1862-41ab-82c2-485837590762"
      },
      "investment_schedule_id": null
    }
  ]
}
```
