# shiny-carnival

## cRPC toy stats

*Values are in %CPU of server tid (System 1 min load avg)*
*C = N of clients; R = N of Replicas*

### cRPC toy

| X   | 1C           | 3C           | 5C           | 8C           | 10C          | 15C          |
| :-: | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: |
| 3R  | 37.54% (.27) | 48.30% (.46) | 54.78% (.40) | 60.89% (.58) | 61.87% (.57) | 62.56% (.66) |
| 5R  | 28.89% (.35) | 38.11% (.38) | 45.93% (.46) | 49.36% (.44) | 50.59% (.60) | 53.39% (.68) |
| 7R  | 22.48% (.40) | 33.49% (.40) | 39.39% (.42) | 42.36% (.59) | 44.99% (.55) | 46.92% (.62) |
| 9R  | 18.67% (.52) | 28.19% (.40) | 32.37% (.40) | 37.87% (.61) | 38.44% (.54) | 39.20% (.56) |
| 11R | 16.71% (.52) | 27.07% (.52) | 30.11% (.50) | 34.10% (.46) | 36.72% (.50) | 34.75% (.64) |
| 13R | 15.27% (.48) | 22.74% (.53) | 26.73% (.55) | 30.09% (.63) | 32.75% (.68) | 32.42% (.65) |
| 15R | 13.74% (.51) | 20.82% (.64) | 24.73% (.66) | 28.18% (.71) | 29.39% (.63) | 28.91% (.66) |

### cRPC raft