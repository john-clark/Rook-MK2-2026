# Parts

!!! Note: This printer was designed so it could be printed with PLA and no heated bed, although I have not tested this. YMMV

| Property | Density (g/cm³) | Scale Factor      | Shrinkage   | Tensile Strength (MPa) | Impact Resistance | Hardness / Rigidity      | Abrasion Resistance | Heat Resistance (°C) | UV Resistance | Aging Resistance | Printability                | Biocompatibility                    | Cost        |
| :------- | :-------------- | :---------------- | :---------- | :--------------------- | :---------------- | :----------------------- | :------------------ | :------------------- | :------------ | :--------------- | :-------------------------- | :---------------------------------- | :---------- |
| ASA      | \~1.07          | 100.50%           | 0.4% – 0.7% | \~50–55                | High              | High (Shore D \~70)      | Good                | \~90–100             | Excellent     | High             | Moderate (needs enclosure)  | Limited                             | Medium-High |
| ABS      | \~1.04          | 100.81%           | 0.7% – 1.6% | \~40–50                | Medium-High       | Medium-High              | Moderate            | \~85–100             | Poor          | Low              | Moderate (needs enclosure)  | No                                  | Low-Medium  |
| PETG     | \~1.27          | 100.40%           | 0.2% – 1%   | \~50–60                | High              | Medium                   | Moderate            | \~75–85              | Poor          | Medium           | Easy                        | Limited                             | Medium      |
| PLA      | \~1.24          | 100.30%           | 0.2% – 0.5% | \~45–60                | Low-Medium        | High, but brittle        | Poor                | \~60                 | Poor          | Low              | Very Easy                   | Yes (food-safe grades)              | Low         |
| Nylon    | \~1.12–1.15     | \~100.80%–101.20% | 1.0% – 2.0% | \~60–80                | Very High         | Medium (flexible, tough) | Excellent           | \~100–120            | Poor          | Medium-High      | Difficult (needs enclosure) | Limited (some medical grades exist) | Medium-High |



**For best results use a Material type of ABS, ASA.**

!!! Note: "Nylon (PA) Notes:" Includes multiple variants such as PA6 (stronger, more hygroscopic), PA12 (easier to print, lower moisture absorption), and filled types like carbon fiber (CF) and glass fiber (GF). Filled nylons have significantly reduced shrinkage and higher rigidity, making them better for structural parts, but are more brittle and abrasive to nozzles. All nylons are hygroscopic and require thorough drying before printing.

## Print Settings

**Choose 0.20mm Strength @BBL X1C**

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

This will keep the color consistant

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
