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

Minimum weight: 20

Ship's actual speed depends on the speed of the engine and the ship's mass.

| Ship Mass           | Ship Speed Formula                                               |
| ------------------- | ---------------------------------------------------------------- |
| $\leq 500$          | $ShipSpeed = EngineSpeed$                                        |
| $500 < Mass < 2000$ | $ShipSpeed = EngineSpeed \times (1.22333 - 0.00045 \times Mass)$ |
| $\geq 2000$         | $ShipSpeed = EngineSpeed \times 0.33$                            |

## Fuel Tanks

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

Minimum weight: 20

## Radars

Talking to or scanning other ships in impossible without a radar.

| TL  | Name         | Range |
| --- | ------------ | ----- |
| 1   | Undular      | 1200  |
| 2   | Subtransfer  | 1400  |
| 3   | Octonic      | 1600  |
| 4   | Fascicular   | 1800  |
| 5   | Cathauric    | 2100  |
| 6   | Neurolinear  | 2400  |
| 7   | Ethane       | 2700  |
| 8   | Zero-Contact | 3000  |

Minimum weight: 15

## Scanners

Scanning dominator ships is only possible with a scanner looted from dominators.

| TL  | Name        | Overcomes shields of |
| --- | ----------- | -------------------- |
| 1   | Tracer      | 11%                  |
| 2   | Vortex      | 14%                  |
| 3   | Neuroprobic | 17%                  |
| 4   | Molecular   | 20%                  |
| 5   | Colloidal   | 23%                  |
| 6   | Tecoral     | 26%                  |
| 7   | Deatomic    | 29%                  |
| 8   | Quantifying | 32%                  |

Minimum weight: 15

## Droid

| TL  | Name       | Hull Repair/Day |
| --- | ---------- | --------------- |
| 1   | Biotic     | 5               |
| 2   | Suspensory | 10              |
| 3   | Tracking   | 15              |
| 4   | Tubular    | 20              |
| 5   | Bolide     | 30              |
| 6   | Tensor     | 40              |
| 7   | Dowel      | 50              |
| 8   | Duplex     | 60              |

Minimum weight: 20

## Shield Generators

| TL  | Name         | Damage reduction |
| --- | ------------ | ---------------- |
| 1   | Shortwave    | 11%              |
| 2   | Polarizing   | 13%              |
| 3   | Mesonic      | 16%              |
| 4   | Mesh         | 19%              |
| 5   | Polygon      | 22%              |
| 6   | Zone         | 25%              |
| 7   | Microlevel   | 28%              |
| 8   | Ultraplasmic | 31%              |

Minimum weight: 20

Tha damage of each shot made against a ship is reduced by the shield generator
and then by the hull armor.

$Damage = ShotStrength \times \frac{100 - ShieldPower}{100} - HullArmor$

## Grippers

| TL  | Name         | Max object size | Range |
| --- | ------------ | --------------- | ----- |
| 1   | Activating   | 40              | 100   |
| 2   | Telekinetic  | 50              | 110   |
| 3   | Plasmathread | 60              | 120   |
| 4   | Ectogenic    | 80              | 130   |
| 5   | Piezotropic  | 90              | 140   |
| 6   | Erimetric    | 100             | 150   |
| 7   | Optoundular  | 150             | 175   |
| 8   | Microtonal   | 500             | 200   |

Minimum weight: 20
