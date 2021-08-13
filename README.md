
![Wolley Wheel](wolley_wheel.png)

The Mechanical Project for the Wolley Wheel Module
==================================================

A robot wheel with built-in 2-stage planetary gearbox, motor and controller.

| Specification |      |
| ------------- | ----:|
| Stage 1 ratio | 9.33 |
| Stage 2 ratio |  5.5 |
| Total ratio   | 51.3 |

Parts
-----

### 3D Printable

| Qty | Part        | Material      |
| ---:| ----------- | ------------- |
|   1 | Enclosure   | PLA*          |
|   1 | Back        | PET-G         |
|   1 | Middle      | PLA*          |
|   1 | Carrier     | PET-G         |
|   3 | PlanetGearA | PET-G or PLA* |
|   3 | PlanetGearB | PET-G or PLA* |
|   1 | RingGearA   | PET-G or PLA* |
|   1 | Wheel       | PET-G         |
|   1 | SunGearA    | PET-G         |
|   1 | SunGearB    | PET-G or PLA* |
|   1 | Front       | PLA*          |

_* HTPLA, Tough PLA, PLA+ or PLA with carbon fiber_

### Other Parts

| Qty | Part                                                         |
| ---:| ------------------------------------------------------------ |
|   4 | Socket Screw ISO 4762 - M3x15mm                              |
|   6 | Socket Screw ISO 4762 - M3x4mm                               |
|   2 | Socket Screw ISO 4762 - M2.5x6mm                             |
|   1 | M3 Hex-standoff 11mm (Ettinger 05.03.111)                    |
|   3 | M3 Threaded Circular Spacer 4mm Ø4.76mm (Harwin R30-5000402) |
|   4 | M3 Threaded Insert (Ruthex RX-M3x5.7)                        |
|   3 | Neodym Magnet, 2x4mm (Meder NdFeB N35)                       |
|   1 | DC Motor (ex. Mabuchi RS-385PV-2465)                         |
|   1 | ECU (Wolley MotorECU)                                        |

How to Build
------------

1. Print all parts without cogs with 0.25 mm layer height or thinner.
2. Print all other parts with 0.20 mm layer height or thinner.
3. Sandpaper all parts slightly and make sure they were printed as intended.
   This might not be needed at all for the parts printed in PET-G.
4. Assemble the motor, _MotorECU_ and _Back_.
5. Glue _SunGearA_ on the motor shaft using Loctite 648 and the mount tool.
6. Assemble the rest according to the explosion drawing. 
7. Make sure it is functional by rotating the wheel by hand. If it does not
   work, more sandpaping or better printing may be neccessary.
8. Run the motor for a bit to make the gearbox smoother. This could also be
   done by hand.
9. Take it apart and lubricate the internal parts slightly with lithium grease.
10. Assemble it again and use Loctite thread lock for the M3x4mm screws for
    preventing them from loosening.
