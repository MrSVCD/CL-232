# Current Limiter
![](CurrentLimiterPCB.png)

This is a simple PCB that uses a LM317 and a 68Ω resistor to make a 20mA current limiter that adjusts for different voltages (up to 40volts).

The circuit is so simple that a PCB is not really necessary. If you build one without a PCB, remember that the exposed metal on the TO-220 version is connected to voltage out and should be isolated if it needs cooling.

## Resistor value examples:
| Target mA | Exact Ω | Nearest E24 resistor| Resulting mA |
|----------:|--------:|------------:|----------:|
|         5 |  256,00 |         270 |      4,74 |
|        10 |  128,00 |         120 |     10,67 |
|        20 |   64,00 |          62 |     20,65 |
|        30 |   42,67 |          43 |     29,77 |
|        40 |   32,00 |          33 |     38,79 |
|        50 |   25,60 |          27 |     47,41 |

![](CurrentLimiterSCH.png)
