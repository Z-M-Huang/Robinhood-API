# /options/orders/

## Request GET Authorized:

Query Strings:

- chain_ids: (uuid, like `09b4a6b7-0ce6-4589-8991-67467ddae837`)

## Response:

```json
{
  "next": null,
  "previous": null,
  "results": [
    {
      "cancel_url": "https://api.robinhood.com/options/orders/1ffae154-0bca-4b90-a191-370ea4a77f47/cancel/",
      "canceled_quantity": "0.00000",
      "created_at": "2020-08-21T08:22:40.847244Z",
      "direction": "credit",
      "id": "1ffae154-0bca-4b90-a191-370ea4a77f47",
      "legs": [
        {
          "executions": [],
          "id": "af66baac-4008-4d46-911e-7b766941f424",
          "option": "https://api.robinhood.com/options/instruments/6d29103c-f0a2-4270-9563-a7678a7b2cf6/",
          "position_effect": "close",
          "ratio_quantity": 1,
          "side": "sell"
        }
      ],
      "pending_quantity": "1.00000",
      "premium": "5.00000000",
      "processed_premium": "0.0000",
      "price": "0.05000000",
      "processed_quantity": "0.00000",
      "quantity": "1.00000",
      "ref_id": "913f595d-d4c6-450c-b498-c56fffc3c35f",
      "state": "queued",
      "time_in_force": "gfd",
      "trigger": "immediate",
      "type": "limit",
      "updated_at": "2020-08-21T08:22:41.151989Z",
      "chain_id": "09b4a6b7-0ce6-4589-8991-67467ddae837",
      "chain_symbol": "PAYS",
      "response_category": null,
      "opening_strategy": null,
      "closing_strategy": "long_call",
      "stop_price": null
    },
    {
      "cancel_url": null,
      "canceled_quantity": "1.00000",
      "created_at": "2020-08-20T16:21:05.432518Z",
      "direction": "credit",
      "id": "ac8d5cd6-d3d1-4ee4-8d84-a06bf3243adc",
      "legs": [
        {
          "executions": [],
          "id": "14d3868a-7ada-47c8-aa69-7457f0afd7e5",
          "option": "https://api.robinhood.com/options/instruments/6d29103c-f0a2-4270-9563-a7678a7b2cf6/",
          "position_effect": "close",
          "ratio_quantity": 1,
          "side": "sell"
        }
      ],
      "pending_quantity": "0.00000",
      "premium": "5.00000000",
      "processed_premium": "0.0000",
      "price": "0.05000000",
      "processed_quantity": "0.00000",
      "quantity": "1.00000",
      "ref_id": "99dfb714-d922-44c6-a3a0-d0c81ba0f597",
      "state": "cancelled",
      "time_in_force": "gfd",
      "trigger": "immediate",
      "type": "limit",
      "updated_at": "2020-08-20T20:30:12.637101Z",
      "chain_id": "09b4a6b7-0ce6-4589-8991-67467ddae837",
      "chain_symbol": "PAYS",
      "response_category": "end_of_day",
      "opening_strategy": null,
      "closing_strategy": "long_call",
      "stop_price": null
    }
  ]
}
```
