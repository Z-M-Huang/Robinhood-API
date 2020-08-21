# /marketdata/historicals/

## Request GET Authorized:

Query Strings:

- bounds: trading
- ids (comma delimited uuid strings, like `d5bd04b5-a963-4e20-bce4-7a1d916d78fd,ffb40d09-3a49-4e9d-94f6-010c2778d473`)
- interval: 5minute
- span: day

## Response:

```json
{
  "results": [
    {
      "quote": "https://api.robinhood.com/quotes/d5bd04b5-a963-4e20-bce4-7a1d916d78fd/",
      "symbol": "KR",
      "interval": "5minute",
      "span": "day",
      "bounds": "trading",
      "previous_close_price": "36.220000",
      "previous_close_time": "2020-08-19T20:00:00Z",
      "open_price": "36.210000",
      "open_time": "2020-08-20T13:00:00Z",
      "instrument": "https://api.robinhood.com/instruments/d5bd04b5-a963-4e20-bce4-7a1d916d78fd/",
      "historicals": [
        {
          "begins_at": "2020-08-20T13:00:00Z",
          "open_price": "36.210000",
          "close_price": "36.210000",
          "high_price": "36.210000",
          "low_price": "36.210000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:05:00Z",
          "open_price": "36.210000",
          "close_price": "36.210000",
          "high_price": "36.210000",
          "low_price": "36.210000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:10:00Z",
          "open_price": "36.210000",
          "close_price": "36.210000",
          "high_price": "36.210000",
          "low_price": "36.210000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:15:00Z",
          "open_price": "36.210000",
          "close_price": "36.210000",
          "high_price": "36.210000",
          "low_price": "36.210000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:20:00Z",
          "open_price": "36.210000",
          "close_price": "36.210000",
          "high_price": "36.210000",
          "low_price": "36.210000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:25:00Z",
          "open_price": "36.210000",
          "close_price": "36.210000",
          "high_price": "36.210000",
          "low_price": "36.210000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:30:00Z",
          "open_price": "36.210000",
          "close_price": "36.240000",
          "high_price": "36.400000",
          "low_price": "36.190000",
          "volume": 49245,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:35:00Z",
          "open_price": "36.235000",
          "close_price": "36.160000",
          "high_price": "36.240000",
          "low_price": "36.080000",
          "volume": 21270,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:40:00Z",
          "open_price": "36.150000",
          "close_price": "36.070000",
          "high_price": "36.185000",
          "low_price": "36.055000",
          "volume": 21987,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:45:00Z",
          "open_price": "36.080000",
          "close_price": "36.180000",
          "high_price": "36.185000",
          "low_price": "36.074000",
          "volume": 18894,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:50:00Z",
          "open_price": "36.193500",
          "close_price": "36.080000",
          "high_price": "36.195000",
          "low_price": "36.075000",
          "volume": 16340,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:55:00Z",
          "open_price": "36.100000",
          "close_price": "36.165000",
          "high_price": "36.170000",
          "low_price": "36.100000",
          "volume": 14157,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:00:00Z",
          "open_price": "36.160000",
          "close_price": "36.115000",
          "high_price": "36.175000",
          "low_price": "36.075800",
          "volume": 27453,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:05:00Z",
          "open_price": "36.090000",
          "close_price": "36.060000",
          "high_price": "36.095000",
          "low_price": "36.050000",
          "volume": 22972,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:10:00Z",
          "open_price": "36.060000",
          "close_price": "36.090000",
          "high_price": "36.090000",
          "low_price": "36.040000",
          "volume": 20910,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:15:00Z",
          "open_price": "36.085000",
          "close_price": "36.153200",
          "high_price": "36.160000",
          "low_price": "36.050000",
          "volume": 35115,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:20:00Z",
          "open_price": "36.160000",
          "close_price": "36.185000",
          "high_price": "36.210000",
          "low_price": "36.135000",
          "volume": 15273,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:25:00Z",
          "open_price": "36.190000",
          "close_price": "36.210000",
          "high_price": "36.210000",
          "low_price": "36.160600",
          "volume": 33828,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:30:00Z",
          "open_price": "36.205000",
          "close_price": "36.180000",
          "high_price": "36.220000",
          "low_price": "36.140000",
          "volume": 18613,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:35:00Z",
          "open_price": "36.180000",
          "close_price": "36.110000",
          "high_price": "36.180000",
          "low_price": "36.105000",
          "volume": 9439,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:40:00Z",
          "open_price": "36.125000",
          "close_price": "36.055000",
          "high_price": "36.125000",
          "low_price": "36.050000",
          "volume": 30658,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:45:00Z",
          "open_price": "36.055000",
          "close_price": "36.081800",
          "high_price": "36.115000",
          "low_price": "36.050000",
          "volume": 21812,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:50:00Z",
          "open_price": "36.085000",
          "close_price": "36.115000",
          "high_price": "36.135000",
          "low_price": "36.085000",
          "volume": 31876,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:55:00Z",
          "open_price": "36.090000",
          "close_price": "36.045000",
          "high_price": "36.090000",
          "low_price": "36.025000",
          "volume": 38794,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:00:00Z",
          "open_price": "36.050000",
          "close_price": "36.125000",
          "high_price": "36.130000",
          "low_price": "36.050000",
          "volume": 14671,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:05:00Z",
          "open_price": "36.110000",
          "close_price": "36.065000",
          "high_price": "36.125000",
          "low_price": "36.061800",
          "volume": 21962,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:10:00Z",
          "open_price": "36.065000",
          "close_price": "36.055000",
          "high_price": "36.065000",
          "low_price": "35.970000",
          "volume": 73259,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:15:00Z",
          "open_price": "36.055000",
          "close_price": "35.980000",
          "high_price": "36.060000",
          "low_price": "35.974300",
          "volume": 22602,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:20:00Z",
          "open_price": "35.990000",
          "close_price": "36.040000",
          "high_price": "36.070000",
          "low_price": "35.990000",
          "volume": 31248,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:25:00Z",
          "open_price": "36.050000",
          "close_price": "36.042100",
          "high_price": "36.060000",
          "low_price": "36.029900",
          "volume": 16577,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:30:00Z",
          "open_price": "36.040000",
          "close_price": "36.065000",
          "high_price": "36.090000",
          "low_price": "36.030000",
          "volume": 57584,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:35:00Z",
          "open_price": "36.075000",
          "close_price": "36.077900",
          "high_price": "36.090000",
          "low_price": "36.060000",
          "volume": 15083,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:40:00Z",
          "open_price": "36.080000",
          "close_price": "36.080000",
          "high_price": "36.100000",
          "low_price": "36.080000",
          "volume": 12107,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:45:00Z",
          "open_price": "36.085000",
          "close_price": "36.070000",
          "high_price": "36.090000",
          "low_price": "36.065000",
          "volume": 10679,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:50:00Z",
          "open_price": "36.065000",
          "close_price": "36.025000",
          "high_price": "36.065000",
          "low_price": "36.025000",
          "volume": 9553,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:55:00Z",
          "open_price": "36.030000",
          "close_price": "36.035000",
          "high_price": "36.055000",
          "low_price": "36.025000",
          "volume": 8976,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:00:00Z",
          "open_price": "36.035000",
          "close_price": "36.055000",
          "high_price": "36.075000",
          "low_price": "36.035000",
          "volume": 11830,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:05:00Z",
          "open_price": "36.060000",
          "close_price": "36.060000",
          "high_price": "36.075000",
          "low_price": "36.040000",
          "volume": 5627,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:10:00Z",
          "open_price": "36.070000",
          "close_price": "36.080000",
          "high_price": "36.130000",
          "low_price": "36.060000",
          "volume": 85533,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:15:00Z",
          "open_price": "36.070000",
          "close_price": "36.010000",
          "high_price": "36.089000",
          "low_price": "36.005000",
          "volume": 36823,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:20:00Z",
          "open_price": "36.020000",
          "close_price": "36.032000",
          "high_price": "36.045000",
          "low_price": "35.990000",
          "volume": 8449,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:25:00Z",
          "open_price": "36.030000",
          "close_price": "36.015000",
          "high_price": "36.050000",
          "low_price": "36.014100",
          "volume": 7806,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:30:00Z",
          "open_price": "36.005000",
          "close_price": "36.035000",
          "high_price": "36.045000",
          "low_price": "35.995000",
          "volume": 10055,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:35:00Z",
          "open_price": "36.049900",
          "close_price": "36.015000",
          "high_price": "36.049900",
          "low_price": "36.010000",
          "volume": 12634,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:40:00Z",
          "open_price": "36.020000",
          "close_price": "35.990000",
          "high_price": "36.030000",
          "low_price": "35.990000",
          "volume": 15919,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:45:00Z",
          "open_price": "35.985000",
          "close_price": "35.995000",
          "high_price": "36.005000",
          "low_price": "35.983300",
          "volume": 7567,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:50:00Z",
          "open_price": "35.995000",
          "close_price": "35.940000",
          "high_price": "36.010000",
          "low_price": "35.930000",
          "volume": 19888,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:55:00Z",
          "open_price": "35.945000",
          "close_price": "35.975000",
          "high_price": "35.990000",
          "low_price": "35.932100",
          "volume": 32115,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:00:00Z",
          "open_price": "35.970000",
          "close_price": "35.970000",
          "high_price": "36.000000",
          "low_price": "35.965000",
          "volume": 7559,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:05:00Z",
          "open_price": "35.970000",
          "close_price": "35.905000",
          "high_price": "35.970000",
          "low_price": "35.900000",
          "volume": 14814,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:10:00Z",
          "open_price": "35.910000",
          "close_price": "35.865000",
          "high_price": "35.915000",
          "low_price": "35.850000",
          "volume": 23061,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:15:00Z",
          "open_price": "35.865000",
          "close_price": "35.860000",
          "high_price": "35.870000",
          "low_price": "35.855000",
          "volume": 5473,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:20:00Z",
          "open_price": "35.852100",
          "close_price": "35.840000",
          "high_price": "35.870000",
          "low_price": "35.835000",
          "volume": 8015,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:25:00Z",
          "open_price": "35.830000",
          "close_price": "35.804000",
          "high_price": "35.850000",
          "low_price": "35.800000",
          "volume": 7555,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:30:00Z",
          "open_price": "35.800000",
          "close_price": "35.820000",
          "high_price": "35.830000",
          "low_price": "35.800000",
          "volume": 15425,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:35:00Z",
          "open_price": "35.820000",
          "close_price": "35.800000",
          "high_price": "35.840000",
          "low_price": "35.791000",
          "volume": 13932,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:40:00Z",
          "open_price": "35.795000",
          "close_price": "35.835000",
          "high_price": "35.840000",
          "low_price": "35.780000",
          "volume": 13695,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:45:00Z",
          "open_price": "35.833300",
          "close_price": "35.870000",
          "high_price": "35.885000",
          "low_price": "35.820000",
          "volume": 8703,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:50:00Z",
          "open_price": "35.865000",
          "close_price": "35.840000",
          "high_price": "35.890000",
          "low_price": "35.830000",
          "volume": 9612,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:55:00Z",
          "open_price": "35.830000",
          "close_price": "35.795000",
          "high_price": "35.830000",
          "low_price": "35.795000",
          "volume": 6485,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:00:00Z",
          "open_price": "35.790000",
          "close_price": "35.820000",
          "high_price": "35.825000",
          "low_price": "35.780000",
          "volume": 10163,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:05:00Z",
          "open_price": "35.815000",
          "close_price": "35.800000",
          "high_price": "35.827900",
          "low_price": "35.780000",
          "volume": 19892,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:10:00Z",
          "open_price": "35.805000",
          "close_price": "35.845000",
          "high_price": "35.850000",
          "low_price": "35.800000",
          "volume": 10840,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:15:00Z",
          "open_price": "35.845000",
          "close_price": "35.900000",
          "high_price": "35.910000",
          "low_price": "35.845000",
          "volume": 26787,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:20:00Z",
          "open_price": "35.910000",
          "close_price": "35.945000",
          "high_price": "35.985000",
          "low_price": "35.905000",
          "volume": 48593,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:25:00Z",
          "open_price": "35.945000",
          "close_price": "35.940000",
          "high_price": "35.960000",
          "low_price": "35.940000",
          "volume": 18748,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:30:00Z",
          "open_price": "35.940000",
          "close_price": "35.950000",
          "high_price": "35.950000",
          "low_price": "35.940000",
          "volume": 12339,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:35:00Z",
          "open_price": "35.945000",
          "close_price": "35.955000",
          "high_price": "35.960000",
          "low_price": "35.940000",
          "volume": 11492,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:40:00Z",
          "open_price": "35.960000",
          "close_price": "35.950000",
          "high_price": "35.970000",
          "low_price": "35.940000",
          "volume": 9831,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:45:00Z",
          "open_price": "35.950000",
          "close_price": "35.955000",
          "high_price": "35.960000",
          "low_price": "35.940000",
          "volume": 7252,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:50:00Z",
          "open_price": "35.955000",
          "close_price": "35.927000",
          "high_price": "35.956000",
          "low_price": "35.925000",
          "volume": 6107,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:55:00Z",
          "open_price": "35.920000",
          "close_price": "35.915000",
          "high_price": "35.940000",
          "low_price": "35.910000",
          "volume": 16236,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:00:00Z",
          "open_price": "35.910000",
          "close_price": "35.965000",
          "high_price": "35.970000",
          "low_price": "35.905000",
          "volume": 26282,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:05:00Z",
          "open_price": "35.965000",
          "close_price": "35.955000",
          "high_price": "35.975000",
          "low_price": "35.950000",
          "volume": 20991,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:10:00Z",
          "open_price": "35.955000",
          "close_price": "35.940000",
          "high_price": "35.970000",
          "low_price": "35.930000",
          "volume": 18672,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:15:00Z",
          "open_price": "35.940000",
          "close_price": "35.915000",
          "high_price": "35.950000",
          "low_price": "35.910000",
          "volume": 24483,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:20:00Z",
          "open_price": "35.915000",
          "close_price": "35.893300",
          "high_price": "35.930000",
          "low_price": "35.885000",
          "volume": 29250,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:25:00Z",
          "open_price": "35.890000",
          "close_price": "35.920000",
          "high_price": "35.930000",
          "low_price": "35.885000",
          "volume": 17543,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:30:00Z",
          "open_price": "35.918900",
          "close_price": "35.920000",
          "high_price": "35.945000",
          "low_price": "35.910000",
          "volume": 28000,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:35:00Z",
          "open_price": "35.910000",
          "close_price": "35.905000",
          "high_price": "35.930000",
          "low_price": "35.890000",
          "volume": 27619,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:40:00Z",
          "open_price": "35.905000",
          "close_price": "35.930000",
          "high_price": "35.930000",
          "low_price": "35.891000",
          "volume": 22341,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:45:00Z",
          "open_price": "35.930000",
          "close_price": "35.895000",
          "high_price": "35.930000",
          "low_price": "35.895000",
          "volume": 45999,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:50:00Z",
          "open_price": "35.890000",
          "close_price": "35.845000",
          "high_price": "35.900000",
          "low_price": "35.835000",
          "volume": 71638,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:55:00Z",
          "open_price": "35.850000",
          "close_price": "35.920000",
          "high_price": "35.940000",
          "low_price": "35.850000",
          "volume": 95811,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:00:00Z",
          "open_price": "35.920000",
          "close_price": "36.080000",
          "high_price": "36.080000",
          "low_price": "35.920000",
          "volume": 45079,
          "session": "post",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:05:00Z",
          "open_price": "35.750000",
          "close_price": "35.750000",
          "high_price": "35.750000",
          "low_price": "35.750000",
          "volume": 1970,
          "session": "post",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:10:00Z",
          "open_price": "35.750000",
          "close_price": "35.750000",
          "high_price": "35.750000",
          "low_price": "35.750000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:15:00Z",
          "open_price": "36.100000",
          "close_price": "35.750000",
          "high_price": "36.100000",
          "low_price": "35.750000",
          "volume": 3999,
          "session": "post",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:20:00Z",
          "open_price": "35.750000",
          "close_price": "35.750000",
          "high_price": "35.750000",
          "low_price": "35.750000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:25:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 173,
          "session": "post",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:30:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 7685,
          "session": "post",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:35:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:40:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:45:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:50:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:55:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:00:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:05:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 346,
          "session": "post",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T21:10:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:15:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:20:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:25:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:30:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:35:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:40:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:45:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:50:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:55:00Z",
          "open_price": "35.920000",
          "close_price": "35.920000",
          "high_price": "35.920000",
          "low_price": "35.920000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        }
      ],
      "InstrumentID": "d5bd04b5-a963-4e20-bce4-7a1d916d78fd"
    },
    {
      "quote": "https://api.robinhood.com/quotes/ffb40d09-3a49-4e9d-94f6-010c2778d473/",
      "symbol": "TCEHY",
      "interval": "5minute",
      "span": "day",
      "bounds": "trading",
      "previous_close_price": "64.800000",
      "previous_close_time": "2020-08-19T20:00:00Z",
      "open_price": "64.920000",
      "open_time": "2020-08-20T13:00:00Z",
      "instrument": "https://api.robinhood.com/instruments/ffb40d09-3a49-4e9d-94f6-010c2778d473/",
      "historicals": [
        {
          "begins_at": "2020-08-20T13:00:00Z",
          "open_price": "64.920000",
          "close_price": "64.920000",
          "high_price": "64.920000",
          "low_price": "64.920000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:05:00Z",
          "open_price": "64.920000",
          "close_price": "64.920000",
          "high_price": "64.920000",
          "low_price": "64.920000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:10:00Z",
          "open_price": "64.920000",
          "close_price": "64.920000",
          "high_price": "64.920000",
          "low_price": "64.920000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:15:00Z",
          "open_price": "64.920000",
          "close_price": "64.920000",
          "high_price": "64.920000",
          "low_price": "64.920000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:20:00Z",
          "open_price": "64.920000",
          "close_price": "64.920000",
          "high_price": "64.920000",
          "low_price": "64.920000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:25:00Z",
          "open_price": "64.920000",
          "close_price": "64.920000",
          "high_price": "64.920000",
          "low_price": "64.920000",
          "volume": 0,
          "session": "pre",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T13:30:00Z",
          "open_price": "64.920000",
          "close_price": "65.040000",
          "high_price": "65.270000",
          "low_price": "64.920000",
          "volume": 43975,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:35:00Z",
          "open_price": "65.090000",
          "close_price": "65.140000",
          "high_price": "65.150000",
          "low_price": "65.050000",
          "volume": 21312,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:40:00Z",
          "open_price": "65.140000",
          "close_price": "65.200000",
          "high_price": "65.200000",
          "low_price": "65.080000",
          "volume": 41253,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:45:00Z",
          "open_price": "65.210000",
          "close_price": "65.340000",
          "high_price": "65.340000",
          "low_price": "65.210000",
          "volume": 43275,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:50:00Z",
          "open_price": "65.335000",
          "close_price": "65.304000",
          "high_price": "65.340000",
          "low_price": "65.230000",
          "volume": 13714,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T13:55:00Z",
          "open_price": "65.330000",
          "close_price": "65.300000",
          "high_price": "65.370000",
          "low_price": "65.280000",
          "volume": 26175,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:00:00Z",
          "open_price": "65.330000",
          "close_price": "65.280000",
          "high_price": "65.330000",
          "low_price": "65.250000",
          "volume": 4526,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:05:00Z",
          "open_price": "65.270000",
          "close_price": "65.260000",
          "high_price": "65.290000",
          "low_price": "65.200000",
          "volume": 10882,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:10:00Z",
          "open_price": "65.270000",
          "close_price": "65.220000",
          "high_price": "65.330000",
          "low_price": "65.220000",
          "volume": 17721,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:15:00Z",
          "open_price": "65.279000",
          "close_price": "65.302000",
          "high_price": "65.330000",
          "low_price": "65.230000",
          "volume": 32636,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:20:00Z",
          "open_price": "65.315000",
          "close_price": "65.300000",
          "high_price": "65.320000",
          "low_price": "65.250000",
          "volume": 35375,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:25:00Z",
          "open_price": "65.315000",
          "close_price": "65.350000",
          "high_price": "65.370000",
          "low_price": "65.315000",
          "volume": 27631,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:30:00Z",
          "open_price": "65.355000",
          "close_price": "65.360000",
          "high_price": "65.360000",
          "low_price": "65.350000",
          "volume": 27124,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:35:00Z",
          "open_price": "65.360000",
          "close_price": "65.400000",
          "high_price": "65.430000",
          "low_price": "65.360000",
          "volume": 18971,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:40:00Z",
          "open_price": "65.400000",
          "close_price": "65.370000",
          "high_price": "65.410000",
          "low_price": "65.350000",
          "volume": 5309,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:45:00Z",
          "open_price": "65.370000",
          "close_price": "65.440000",
          "high_price": "65.440000",
          "low_price": "65.355000",
          "volume": 6135,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:50:00Z",
          "open_price": "65.450000",
          "close_price": "65.480000",
          "high_price": "65.490000",
          "low_price": "65.450000",
          "volume": 5561,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T14:55:00Z",
          "open_price": "65.450000",
          "close_price": "65.330000",
          "high_price": "65.480000",
          "low_price": "65.330000",
          "volume": 12855,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:00:00Z",
          "open_price": "65.330000",
          "close_price": "65.290000",
          "high_price": "65.400000",
          "low_price": "65.290000",
          "volume": 7639,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:05:00Z",
          "open_price": "65.290000",
          "close_price": "65.250000",
          "high_price": "65.340000",
          "low_price": "65.250000",
          "volume": 9040,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:10:00Z",
          "open_price": "65.250000",
          "close_price": "65.220000",
          "high_price": "65.270000",
          "low_price": "65.200000",
          "volume": 18279,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:15:00Z",
          "open_price": "65.280000",
          "close_price": "65.290000",
          "high_price": "65.330000",
          "low_price": "65.265000",
          "volume": 7582,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:20:00Z",
          "open_price": "65.290000",
          "close_price": "65.295000",
          "high_price": "65.310000",
          "low_price": "65.270000",
          "volume": 3687,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:25:00Z",
          "open_price": "65.310000",
          "close_price": "65.320600",
          "high_price": "65.480000",
          "low_price": "65.310000",
          "volume": 31723,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:30:00Z",
          "open_price": "65.440000",
          "close_price": "65.500000",
          "high_price": "65.500000",
          "low_price": "65.440000",
          "volume": 41544,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:35:00Z",
          "open_price": "65.500000",
          "close_price": "65.520000",
          "high_price": "65.590000",
          "low_price": "65.500000",
          "volume": 15448,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:40:00Z",
          "open_price": "65.550000",
          "close_price": "65.600000",
          "high_price": "65.620000",
          "low_price": "65.510000",
          "volume": 13633,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:45:00Z",
          "open_price": "65.600000",
          "close_price": "65.620000",
          "high_price": "65.620000",
          "low_price": "65.590000",
          "volume": 25534,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:50:00Z",
          "open_price": "65.620000",
          "close_price": "65.660000",
          "high_price": "65.660000",
          "low_price": "65.600200",
          "volume": 5899,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T15:55:00Z",
          "open_price": "65.635000",
          "close_price": "65.690000",
          "high_price": "65.690000",
          "low_price": "65.620000",
          "volume": 10179,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:00:00Z",
          "open_price": "65.690000",
          "close_price": "65.735000",
          "high_price": "65.740000",
          "low_price": "65.650000",
          "volume": 10716,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:05:00Z",
          "open_price": "65.730000",
          "close_price": "65.840000",
          "high_price": "65.860000",
          "low_price": "65.730000",
          "volume": 21917,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:10:00Z",
          "open_price": "65.850000",
          "close_price": "65.861000",
          "high_price": "65.890000",
          "low_price": "65.850000",
          "volume": 11869,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:15:00Z",
          "open_price": "65.860000",
          "close_price": "65.899900",
          "high_price": "65.940000",
          "low_price": "65.860000",
          "volume": 36671,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:20:00Z",
          "open_price": "65.875000",
          "close_price": "65.890000",
          "high_price": "65.890000",
          "low_price": "65.830000",
          "volume": 18868,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:25:00Z",
          "open_price": "65.875000",
          "close_price": "65.840000",
          "high_price": "65.875000",
          "low_price": "65.820000",
          "volume": 13303,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:30:00Z",
          "open_price": "65.830000",
          "close_price": "65.766000",
          "high_price": "65.830000",
          "low_price": "65.740000",
          "volume": 12518,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:35:00Z",
          "open_price": "65.775000",
          "close_price": "65.740000",
          "high_price": "65.800000",
          "low_price": "65.730000",
          "volume": 65591,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:40:00Z",
          "open_price": "65.730000",
          "close_price": "65.780000",
          "high_price": "65.790000",
          "low_price": "65.720000",
          "volume": 6924,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:45:00Z",
          "open_price": "65.780000",
          "close_price": "65.675000",
          "high_price": "65.780000",
          "low_price": "65.675000",
          "volume": 14164,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:50:00Z",
          "open_price": "65.700000",
          "close_price": "65.755000",
          "high_price": "65.780000",
          "low_price": "65.650000",
          "volume": 29135,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T16:55:00Z",
          "open_price": "65.760000",
          "close_price": "65.744000",
          "high_price": "65.780000",
          "low_price": "65.744000",
          "volume": 1338,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:00:00Z",
          "open_price": "65.760000",
          "close_price": "65.860000",
          "high_price": "65.890000",
          "low_price": "65.755000",
          "volume": 27575,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:05:00Z",
          "open_price": "65.860000",
          "close_price": "65.835000",
          "high_price": "65.890000",
          "low_price": "65.800000",
          "volume": 6670,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:10:00Z",
          "open_price": "65.840000",
          "close_price": "65.900000",
          "high_price": "65.900000",
          "low_price": "65.840000",
          "volume": 20977,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:15:00Z",
          "open_price": "65.900000",
          "close_price": "65.970000",
          "high_price": "66.000000",
          "low_price": "65.900000",
          "volume": 28239,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:20:00Z",
          "open_price": "65.982000",
          "close_price": "65.921000",
          "high_price": "66.000000",
          "low_price": "65.910000",
          "volume": 8612,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:25:00Z",
          "open_price": "65.960000",
          "close_price": "66.000000",
          "high_price": "66.000000",
          "low_price": "65.950000",
          "volume": 16416,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:30:00Z",
          "open_price": "65.980000",
          "close_price": "65.950000",
          "high_price": "66.050000",
          "low_price": "65.950000",
          "volume": 76828,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:35:00Z",
          "open_price": "65.950000",
          "close_price": "66.000000",
          "high_price": "66.010000",
          "low_price": "65.950000",
          "volume": 16211,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:40:00Z",
          "open_price": "65.970000",
          "close_price": "65.987900",
          "high_price": "66.000000",
          "low_price": "65.970000",
          "volume": 25619,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:45:00Z",
          "open_price": "65.990000",
          "close_price": "65.910000",
          "high_price": "66.000000",
          "low_price": "65.900000",
          "volume": 16499,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:50:00Z",
          "open_price": "65.890000",
          "close_price": "65.920000",
          "high_price": "65.940000",
          "low_price": "65.860000",
          "volume": 11751,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T17:55:00Z",
          "open_price": "65.910000",
          "close_price": "65.850000",
          "high_price": "65.950000",
          "low_price": "65.850000",
          "volume": 5655,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:00:00Z",
          "open_price": "65.909500",
          "close_price": "65.930000",
          "high_price": "65.930000",
          "low_price": "65.860000",
          "volume": 19311,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:05:00Z",
          "open_price": "65.910000",
          "close_price": "65.920000",
          "high_price": "65.940000",
          "low_price": "65.900000",
          "volume": 18786,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:10:00Z",
          "open_price": "65.934000",
          "close_price": "65.900000",
          "high_price": "65.940000",
          "low_price": "65.860000",
          "volume": 9888,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:15:00Z",
          "open_price": "65.900000",
          "close_price": "65.910000",
          "high_price": "65.940000",
          "low_price": "65.900000",
          "volume": 10614,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:20:00Z",
          "open_price": "65.940000",
          "close_price": "66.005000",
          "high_price": "66.010000",
          "low_price": "65.915000",
          "volume": 24878,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:25:00Z",
          "open_price": "66.005000",
          "close_price": "65.965000",
          "high_price": "66.005000",
          "low_price": "65.920000",
          "volume": 8238,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:30:00Z",
          "open_price": "65.945000",
          "close_price": "65.984000",
          "high_price": "65.990000",
          "low_price": "65.934000",
          "volume": 18048,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:35:00Z",
          "open_price": "65.980000",
          "close_price": "65.993000",
          "high_price": "66.010000",
          "low_price": "65.970000",
          "volume": 20219,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:40:00Z",
          "open_price": "65.990000",
          "close_price": "65.950000",
          "high_price": "66.000000",
          "low_price": "65.930000",
          "volume": 21323,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:45:00Z",
          "open_price": "65.970000",
          "close_price": "66.010000",
          "high_price": "66.010000",
          "low_price": "65.960000",
          "volume": 47606,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:50:00Z",
          "open_price": "66.005000",
          "close_price": "66.010000",
          "high_price": "66.010000",
          "low_price": "65.980000",
          "volume": 21950,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T18:55:00Z",
          "open_price": "66.030000",
          "close_price": "65.990000",
          "high_price": "66.050000",
          "low_price": "65.960000",
          "volume": 20394,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:00:00Z",
          "open_price": "66.010000",
          "close_price": "66.050000",
          "high_price": "66.051000",
          "low_price": "65.950000",
          "volume": 38549,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:05:00Z",
          "open_price": "66.050000",
          "close_price": "66.040000",
          "high_price": "66.050000",
          "low_price": "66.000000",
          "volume": 8384,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:10:00Z",
          "open_price": "66.050000",
          "close_price": "66.000000",
          "high_price": "66.060000",
          "low_price": "66.000000",
          "volume": 13983,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:15:00Z",
          "open_price": "66.020000",
          "close_price": "65.940000",
          "high_price": "66.040000",
          "low_price": "65.940000",
          "volume": 55841,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:20:00Z",
          "open_price": "65.940000",
          "close_price": "65.950000",
          "high_price": "65.950000",
          "low_price": "65.860000",
          "volume": 31718,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:25:00Z",
          "open_price": "65.920000",
          "close_price": "65.970000",
          "high_price": "65.970000",
          "low_price": "65.920000",
          "volume": 5389,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:30:00Z",
          "open_price": "65.970000",
          "close_price": "66.060000",
          "high_price": "66.070000",
          "low_price": "65.930000",
          "volume": 36271,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:35:00Z",
          "open_price": "66.080000",
          "close_price": "66.150000",
          "high_price": "66.150000",
          "low_price": "66.050000",
          "volume": 21373,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:40:00Z",
          "open_price": "66.150000",
          "close_price": "66.160000",
          "high_price": "66.215000",
          "low_price": "66.140000",
          "volume": 9672,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:45:00Z",
          "open_price": "66.140000",
          "close_price": "66.190000",
          "high_price": "66.250000",
          "low_price": "66.140000",
          "volume": 6717,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:50:00Z",
          "open_price": "66.150000",
          "close_price": "66.130000",
          "high_price": "66.190000",
          "low_price": "66.110000",
          "volume": 14505,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T19:55:00Z",
          "open_price": "66.150000",
          "close_price": "66.250000",
          "high_price": "66.430000",
          "low_price": "66.080000",
          "volume": 49664,
          "session": "reg",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:00:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 732,
          "session": "post",
          "interpolated": false
        },
        {
          "begins_at": "2020-08-20T20:05:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:10:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:15:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:20:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:25:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:30:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:35:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:40:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:45:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:50:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T20:55:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:00:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:05:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:10:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:15:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:20:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:25:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:30:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:35:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:40:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:45:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:50:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        },
        {
          "begins_at": "2020-08-20T21:55:00Z",
          "open_price": "66.260000",
          "close_price": "66.260000",
          "high_price": "66.260000",
          "low_price": "66.260000",
          "volume": 0,
          "session": "post",
          "interpolated": true
        }
      ],
      "InstrumentID": "ffb40d09-3a49-4e9d-94f6-010c2778d473"
    }
  ]
}
```
