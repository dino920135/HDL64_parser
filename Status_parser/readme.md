Parse **Status Type** and **Status Value** from HDL64 data packet
================================================

------------------------------------------------

GPS time sync
------------------------------------------------

**Status Type Rotation**
Only shows the Status Type related to GPS.

| Hex | ASCII | String | Description |
| :-: | :---: | :----: | :---------- |
| 47  |  71   |   G    |     GPS     |

**GPS Status Values**
GPS Status Values which shows the GPS sync status.

| Hex | ASCII | Description |
| :-: | :---: | :---------- |
| 41  |  65   | A = both "sync signal" and "NMEA time command record"     |
| 56  |  86   | V = "NMEA time command record" only     |
| 50  |  80   | P = "sync signal" only     |
| 00  |  00   | 0 = GPS not connect     |
