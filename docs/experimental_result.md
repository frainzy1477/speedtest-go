# Experimental Result
I randomly select 9 servers to speedtest considering distance from my house. Try speedtesting twice to each server. Testing order is like [speedtest.net] -> [speedtest-go] -> [speedtest-cli] -> [speedtest-cli] -> [speedtest-go] -> [speedtest.net]. To the next server, starting from [speedtest-go], like [speedtest-go] -> [speedtest-cli] -> [speedtest.net] -> [speedtest.net] -> [speedtest-cli] -> [speedtest-go].

## Downlaod (Mbps)

| distance(km) | server id | speediest.net (test1) | speediest.net (test2) | speedtest-go (test1) | speedtest-go (test2) | speedtest-cli (test1) | speedtest-cli (test2) |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 - 1000 (9km) | 6691 | 93.34 | 93.51 | 89.13 | 88.40 | 88.21 | 83.34 |
| 0 - 1000 (194km) | 6368 | 93.45 | 94.20 | 92.93 | 92.26 | 88.45 | 77.07 |
| 0 - 1000 (865km) | 6842 | 88.31 | 89.91 | 91.26 | 93.30 | 67.33 | 87.52 |
| 1000 - 8000 (1982km) | 2589 | 90.24 | 94.05 | 79.61 | 79.52 | 79.16 | 70.36 |
| 1000 - 8000 (4801km) | 3296 | 75.61 | 52.83 | 69.89 | 69.86 | 58.19 | 55.93 |
| 1000 - 8000 (6627km) | 1718 | 42.04 | 43.92 | 39.81 | 54.35 | 44.47 | 31.27 |
| 8000 - 20000 (8972km) | 3409 | 22.11 | 22.74 | 28.21 | 21.82 | 24.78 | 30.59 |
| 8000 - 20000 (13781km) | 3162 | 15.78 | 7.73 | 1.94 | 1.02 | 3.32 | 2.40 |
| 8000 - 20000 (17805km) | 4256 | 1.15 | 1.50 | 1.79 | 1.79 | 6.41 | 3.69 |

## Upload (Mbps)

| distance(km) | server id | speediest.net (test1) | speediest.net (test2) | speedtest-go (test1) | speedtest-go (test2) | speedtest-cli (test1) | speedtest-cli (test2) |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 - 1000 (9km) | 6691 | 52.03 | 48.82 | 40.72 | 43.84 | 36.03 | 36.21
| 0 - 1000 (194km)  | 6368 | 78.30 | 66.92 | 53.98 | 44.07 | 37.26 | 46.98
| 0 - 1000 (865km) | 6842 | 65.34 | 81.96 | 50.27 | 52.57 | 29.42 | 31.08
| 1000 - 8000 (1982km) | 2589 | 89.29 | 58.69 | 80.68 | 56.59 | 42.66 | 44.34
| 1000 - 8000 (4801km) | 3296 | 50.16 | 50.78 | 54.94 | 54.18 | 20.59 | 20.23
| 1000 - 8000 (6627km) | 1718 | 48.48 | 50.71 | 39.81 | 42.21 | 16.16 | 16.72
| 8000 - 20000 (8972km) | 3409 | 18.07 | 20.30 | 20.35 | 24.92 | 5.87 | 3.37
| 8000 - 20000 (13781km) | 3162 | 1.45 | 0.33 | 1.78 | 0.77 | 1.08 | 1.34
| 8000 - 20000 (17805km) | 4256 | 1.16 | 0.30 | 1.00 | 1.11 | 2.37 | 1.42

## Testing Time (sec)

| distance(km) | server id | speediest.net (test1) | speediest.net (test2) | speedtest-go (test1) | speedtest-go (test2) | speedtest-cli (test1) | speedtest-cli (test2) |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 - 1000 (9km) | 6691 | 44.87 | 45.76 | 24.45 | 22.40 | 20.82 | 16.51
| 0 - 1000 (194km)  | 6368 | 43.85 | 42.97 | 19.60 | 22.36 | 22.25 | 24.01
| 0 - 1000 (865km) | 6842 | 46.62 | 46.12 | 21.83 | 26.40 | 39.07 | 24.10
| 1000 - 8000 (1982km) | 2589 | 45.38 | 44.18 | 18.71 | 21.35 | 26.15 | 25.71
| 1000 - 8000 (4801km) | 3296 | 47.92 | 50.52 | 24.71 | 23.47 | 32.07 | 28.53
| 1000 - 8000 (6627km) | 1718 | 40.15 | 41.16 | 28.05 | 30.42 | 31.01 | 27.65
| 8000 - 20000 (8972km) | 3409 | 51.53 | 56.89 | 38.13 | 41.55 | 36.87 | 34.47
| 8000 - 20000 (13781km) | 3162 | 52.75 | 58.10 | 28.78 | 29.91 | 40.75 | 46.88
| 8000 - 20000 (17805km) | 4256 | 37.73 | 40.82 | 33.33 | 32.79 | 37.82 | 50.78