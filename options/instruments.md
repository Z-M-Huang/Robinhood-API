# /options/instruments/

## Request GET Authorized:

Query Strings:

- chain_id: uuid, like: `3f631d1d-d432-4da6-84e1-f00495e853e8`
- expiration_date: yyyy-MM-dd like: `2020-09-18`
- state: `active`
- type: `call` or `put`

## Response:

```json
{
  "next": null,
  "previous": null,
  "results": [
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-07-08T00:14:25.947754Z",
      "expiration_date": "2020-09-18",
      "id": "ea5eff10-a977-4a5a-af4e-155d66d754c9",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "20.0000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-07-08T00:14:25.947762Z",
      "url": "https://api.robinhood.com/options/instruments/ea5eff10-a977-4a5a-af4e-155d66d754c9/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    },
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-06-27T01:23:21.641626Z",
      "expiration_date": "2020-09-18",
      "id": "157935eb-3b27-49da-9dbd-be5104c415a3",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "17.5000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-06-27T01:23:21.641636Z",
      "url": "https://api.robinhood.com/options/instruments/157935eb-3b27-49da-9dbd-be5104c415a3/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    },
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-02-29T05:28:37.291072Z",
      "expiration_date": "2020-09-18",
      "id": "2f4cd04d-33ed-479b-b2a5-e74f012d6344",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "2.5000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-02-29T05:28:37.291080Z",
      "url": "https://api.robinhood.com/options/instruments/2f4cd04d-33ed-479b-b2a5-e74f012d6344/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    },
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-01-18T09:07:04.569482Z",
      "expiration_date": "2020-09-18",
      "id": "d21b027d-59b7-4eee-a7ff-2f17d243092a",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "12.5000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-01-18T09:07:04.569490Z",
      "url": "https://api.robinhood.com/options/instruments/d21b027d-59b7-4eee-a7ff-2f17d243092a/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    },
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-01-18T09:07:04.569318Z",
      "expiration_date": "2020-09-18",
      "id": "2a7e0c62-1163-4d8b-91d3-890bbc02803f",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "5.0000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-01-18T09:07:04.569327Z",
      "url": "https://api.robinhood.com/options/instruments/2a7e0c62-1163-4d8b-91d3-890bbc02803f/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    },
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-01-18T09:07:04.569265Z",
      "expiration_date": "2020-09-18",
      "id": "8a8775d0-9377-4d8d-88de-4f6f2dcc025c",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "7.5000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-01-18T09:07:04.569274Z",
      "url": "https://api.robinhood.com/options/instruments/8a8775d0-9377-4d8d-88de-4f6f2dcc025c/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    },
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-01-18T09:07:04.569210Z",
      "expiration_date": "2020-09-18",
      "id": "973b19f3-0b0e-4014-b0bb-95194a8bf525",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "15.0000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-01-18T09:07:04.569219Z",
      "url": "https://api.robinhood.com/options/instruments/973b19f3-0b0e-4014-b0bb-95194a8bf525/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    },
    {
      "chain_id": "3f631d1d-d432-4da6-84e1-f00495e853e8",
      "chain_symbol": "PAYS",
      "created_at": "2020-01-18T09:07:04.569080Z",
      "expiration_date": "2020-09-18",
      "id": "3c89cd2e-7369-4c96-b97c-f4b2467f7b4b",
      "issue_date": "2019-04-29",
      "min_ticks": {
        "above_tick": "0.10",
        "below_tick": "0.05",
        "cutoff_price": "3.00"
      },
      "rhs_tradability": "untradable",
      "state": "active",
      "strike_price": "10.0000",
      "tradability": "tradable",
      "type": "call",
      "updated_at": "2020-01-18T09:07:04.569098Z",
      "url": "https://api.robinhood.com/options/instruments/3c89cd2e-7369-4c96-b97c-f4b2467f7b4b/",
      "sellout_datetime": "2020-09-18T18:45:00+00:00"
    }
  ]
}
```
