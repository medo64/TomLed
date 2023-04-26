## Parts

|  # | Part                                      | RefDes  | Part Number                |
|---:|-------------------------------------------|---------|----------------------------|
|  1 | DS LED (0805)                             | DS1     | 475-1415-1-ND              |
|  2 | J USB C 2.0, horizontal                   | J1-J2   | 2073-USB4085-GF-ACT-ND     |
|  1 | Q P-MOSFET 30V 1A (SOT-23)                | Q1      | DMP3099L-13DICT-ND         |
|  1 | R 1K 5% 0.125W (0805)                     | R1      | RMCF0805JT1K00             |
|  2 | R 5K1 5% 0.125W (0805)                    | R2-R3   | RMCF0805JT5K10             |
|  1 | R 10K 5% 0.125W (0805)                    | R4      | RMCF0805JT10K0             |
|  2 | R 22K 5% 0.125W (0805)                    | R5-R6   | RMCF0805JT22K0             |
|  1 | S Toggle Side SPDT (3w)                   | S1      | CKN9559-ND                 |


## Specifications

Board size: 46.0 x 17.0 mm ~ 1.3 sqin
Voltage: 5 V
Current: 1.5A


## Current Consumption

This board uses two pulldown resistors (R2 and R3) to signal how much current is
required from charger. Value of 5.1 kΩ allows for pulling up to 3 A.

Board also uses two pullup resistors (R5 and R6) to signal available current and
by default value of 1.5 A will be advertised. If different value is needed, you
can use table below to select it.

| Advertisment      | Resistor |
|-------------------|----------|
| Default USB Power |     56 kΩ |
| 1.5 A / 5 V        |     22 kΩ |
| 3.0 A / 5 V        |     10 kΩ |
