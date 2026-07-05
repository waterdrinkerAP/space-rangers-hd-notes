# Standard equipment

Better equipment becomes available for purchase with the increase of the
galaxy's *Technology Level* (TL)

Reliability of the equipment (how fast it wears out) depends on its race.

|                 |          |        |         |       |           |
| --------------- | -------- | ------ | ------- | ----- | --------- |
| **Race**        | Maloq    | Peleng | Human   | Feyan | Gaal      |
| **Reliability** | Very low | Low    | Average | High  | Very High |

Each type of equipment has a minimum weight it can be.
Dominator and acrynic equipment can have weight slightly lower than the minimum.

## Engines

Minimum weight: 20

| TL  | Name       | Speed | Jump Range |
| --- | ---------- | ----- | ---------- |
| 1   | Diving     | 400   | 17         |
| 2   | Singular   | 450   | 19         |
| 3   | Gillnozzle | 500   | 21         |
| 4   | Flow       | 600   | 25         |
| 5   | Splash     | 700   | 29         |
| 6   | Graviton   | 800   | 33         |
| 7   | Stensor    | 900   | 37         |
| 8   | Temporal   | 1000  | 41         |

Ship's actual speed depends on the speed of the engine and the ship's mass.

| Ship Mass           | Ship Speed Formula                                               |
| ------------------- | ---------------------------------------------------------------- |
| $\leq 500$          | $ShipSpeed = EngineSpeed$                                        |
| $500 < Mass < 2000$ | $ShipSpeed = EngineSpeed \times (1.22333 - 0.00045 \times Mass)$ |
| $\geq 2000$         | $ShipSpeed = EngineSpeed \times 0.33$                            |

## Fuel Tanks

Minimum weight: 20

The total capacity of a fuel tank depends on its size and base capacity.

$TotalCapacity = Size \div 2 + BaseCapacity$

Total capacity is rounded to the nearest even number (Banker's rounding).

| TL  | Name           | Base Capacity |
| --- | -------------- | ------------- |
| 1   | Hyperliquid    | 10            |
| 2   | Condensed      | 15            |
| 3   | Reductional    | 20            |
| 4   | Protovesicular | 25            |
| 5   | Positional     | 30            |
| 6   | Endoclustered  | 35            |
| 7   | Gyroscopic     | 40            |
| 8   | Tecronic       | 45            |
