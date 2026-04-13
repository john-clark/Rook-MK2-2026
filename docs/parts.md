# Parts

!!! Info 
    This printer was designed so it could be printed with PLA and no heated bed, although I have not tested this. YMMV

The following table is to help guide you decision making choice. I have printed my Rooks with parts in various filaments.

| Property | Density (g/cm³) | Scale Factor      | Shrinkage   | Tensile Strength (MPa) | Impact Resistance | Hardness / Rigidity      | Abrasion Resistance | Heat Resistance (°C) | UV Resistance | Aging Resistance | Printability                | Biocompatibility                    | Cost        |
| :------- | :-------------- | :---------------- | :---------- | :--------------------- | :---------------- | :----------------------- | :------------------ | :------------------- | :------------ | :--------------- | :-------------------------- | :---------------------------------- | :---------- |
| ASA      | ~1.07          | 100.50%           | 0.4% – 0.7% | ~50–55                | High              | High (Shore D ~70)      | Good                | ~90–100             | Excellent     | High             | Moderate (needs enclosure)  | Limited                             | Medium-High |
| ABS      | ~1.04          | 100.81%           | 0.7% – 1.6% | ~40–50                | Medium-High       | Medium-High              | Moderate            | ~85–100             | Poor          | Low              | Moderate (needs enclosure)  | No                                  | Low-Medium  |
| PETG     | ~1.27          | 100.40%           | 0.2% – 1%   | ~50–60                | High              | Medium                   | Moderate            | ~75–85              | Poor          | Medium           | Easy                        | Limited                             | Medium      |
| PLA      | ~1.24          | 100.30%           | 0.2% – 0.5% | ~45–60                | Low-Medium        | High, but brittle        | Poor                | ~60                 | Poor          | Low              | Very Easy                   | Yes (food-safe grades)              | Low         |
| Nylon    | ~1.12–1.15     | ~100.80%–101.20% | 1.0% – 2.0% | ~60–80                | Very High         | Medium (flexible, tough) | Excellent           | ~100–120            | Poor          | Medium-High      | Difficult (needs enclosure) | Limited (some medical grades exist) | Medium-High |

**For best results use a Material type of ABS, ASA.**

The density relates to how heavy the product will be when printed. 

!!! Note "Nylon (PA)" 
    Includes multiple variants such as PA6 (stronger, more hygroscopic), PA12 (easier to print, lower moisture absorption), and filled types like carbon fiber (CF) and glass fiber (GF). Filled nylons have significantly reduced shrinkage and higher rigidity, making them better for structural parts, but are more brittle and abrasive to nozzles. All nylons are hygroscopic and require thorough drying before printing. I do not suggest Nylon due to the difficulties printing.

### Shrinkage

Use this [shrinkage calculator](https://go.minimal3dp.com/calc/shrinkage) to calibrate your printer and filament before printing.

#### Further reading

* 3D4Create (2024) [3D Printer Shrinkage: A Complete Guide](https://3d4create.com/3d-printer-shrinkage/)
* Filament2Print (2023) [Shrinkage in 3D Printing: Everything You Need to Know](https://filament2print.com/gb/blog/shrinkage-3d-printing.html)
* Kingroon (2024) [OrcaSlicer vs Bambu Studio: Shrinkage Compensation Settings](https://kingroon.com/blogs/3d-printing-guide/orcaslicer-vs-bambu-studio)
* All3DP (2023) [ASA vs ABS: Material Properties and Printing Characteristics](https://all3dp.com/)

## Print Settings

**Choose 0.20mm Strength** and verify the following settings:

**Quality->Layer Height**

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| Layer Height                | 0.2mm                     |

**Quality->Line width**

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| Default                     | 0.42mm                    |

**Quality->Advanced**

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| Order of walls              | Inner/Outer/Inner         |
| Only one wall on first layer | Check                    |

**Strength->Walls**

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| Wall loops                  | 4                         |
| Embedding the wall into infill | Checked                |

**Strength->Sparse infill**

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| **Sparse infill density**   | 40%                       |
| **Sparse infill pattern**   | Locked zag, gyroid, cubic |

**Strength->Top/bottom shells**

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| Bottom shell layers         | 5                         |

**Speed->Other layers speed**

This will keep the color consistent

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| Outer wall                  | 50mm/s                    |


## Printing

When you layout the parts I suggest printing only one part at a time. That way if it the room is too cold and the parts curl up you are not wasting a lot of filament.

![plate layout](images/plates.png)

If you are having problems with lifting edges I suggest the following settings under **Others->Bed adhesion**.

| **Setting**                 | Value                     |
| :-------------------------- | :------------------------ |
| **Skirt Loops**             | 1                         |
| **Skirt Height**            | 50                        |
| **Brim type**               | Outer brim Only           |
| **Brim Width**              | 5mm (default)             |
| **Brim-Object gap**         | 0.1mm (default)           |


## Extra Parts

If you don't want to buy pins, couplers, idlers and pulleys and rails you can print them. I printed them as place holders on my build until my parts came in. I have not had a chance to determine the longevity of these parts, although I doubt the rails will be sufficient for any use other than observation.

* [Rails](https://www.printables.com/model/338778-mgn9c-rail-and-carriage/files)
* [Couplers](https://www.printables.com/model/1370729-coupler-5mm-to-5mm-shaft)
* [Idlers](https://www.thingiverse.com/thing:1430558)
* [Pulleys](https://www.printables.com/model/1100977-pulleys-gt2-20t-for-a-6mm-belt-and-a-5-mm-shaftbol)
* Pins (link coming soon) - Print horizontal with ASA and you can not break them.

## Customization

You can down load different inserts to customize your Rook.

* [Hexmod](https://www.printables.com/model/1673426-rook-2026-mk2-hexmod)
* [Vanitymod](https://www.printables.com/model/1682095-rook-2026-mk2-vanity-mod)

