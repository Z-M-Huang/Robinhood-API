# /instruments/?ids=

## Request GET Authorized:

Query Strings:

- ids (comma delimited uuid strings, like: `2f9dad1e-3d9e-4ada-8a51-066149ccec30,c05e1896-cb40-4249-8865-d6b458ac44bf,53e96ce4-c11c-4ad9-a0b8-38ae0d57251f,4ff99bec-58e1-4ee4-bc52-b12082707783`)
- active_ionstruments_only: false

## Response:

```json
{
  "count": 4,
  "next": null,
  "previous": null,
  "results": [
    {
      "summary": null,
      "ratings": [],
      "instrument_id": "2f9dad1e-3d9e-4ada-8a51-066149ccec30",
      "ratings_published_at": null
    },
    {
      "summary": {
        "num_buy_ratings": 7,
        "num_hold_ratings": 0,
        "num_sell_ratings": 0
      },
      "ratings": [],
      "instrument_id": "4ff99bec-58e1-4ee4-bc52-b12082707783",
      "ratings_published_at": null
    },
    {
      "summary": null,
      "ratings": [],
      "instrument_id": "53e96ce4-c11c-4ad9-a0b8-38ae0d57251f",
      "ratings_published_at": null
    },
    {
      "summary": null,
      "ratings": [],
      "instrument_id": "c05e1896-cb40-4249-8865-d6b458ac44bf",
      "ratings_published_at": null
    }
  ]
}
```
