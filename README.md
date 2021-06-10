# PrusaSlicer Configuration Bundle
for Cherokee Makerspace 3D Printers

This bundle has been tested on [PrusaSlicer](https://www.prusa3d.com/prusaslicer/) V2.3.0
It is for [Cherokee Makerspace 3D Printers Only]

To use, select Import Config Bundle from the Prusa Slicer File / Import menu.

## Printers Supported

| Printer             | Nozzle    | Bed Size    | Controller | Firmware | Web Interface |
| Prusa i3 Mk2.5s     | 0.4 Steel | 250x210x210 | RAMBo      | Prusa    | OctoPrint     |
| Prusa i3 Mk3s MMU2s | 0.4 Brass | 250x210x210 | RAMBo      | Prusa    | OctoPrint     |
| [Robo 3D R1](https://github.com/Cherokee-Makerspace/Robo-Garolite.git) | 0.8 Steel | 220x200x200 | RAMPS | Marlin | OctoPrint |
| [Robo 3D R1+](https://github.com/Cherokee-Makerspace/Robo-Buildtak.git) | 0.8 Steel | 220x200x200 | RAMPS | Marlin | OctoPrint |
| [Cube Pro](https://github.com/Cherokee-Makerspace/Duet-Cube.git) | 0.4 Vanadium | x | Duet3D | RepRap | Built In |

### Print Settings

### Filament Settings

| Filament |
| Inland PLA |
| Inland PETG |

#### Changlog

| Date | Setting | Notes |
| 06/09/21 | Printer | Removed Robo 3D (0.4) since both Robos are now using 0.8 Nozzles  |
| 06/09/21 | Print / 0.55 DRAFT - Layers | 3 Perimeters, Avoid Crossing Perimeters, External Perimeters First, Nearest Seam Position, External Perimeters First |
| 06/09/21 | Print / 0.55 DRAFT - Infill | 15% Infill, 2.5 Infill Anchor, 10mm Max Infill Anchor |
| 06/09/21 | Print / 0.55 DRAFT - Output | Check Verbose G-code |
| 06/09/21 | Print / 0.40 QUALITY - Layers | 3 Perimeters, Avoid Crossing Perimeters, External Perimeters First, Nearest Seam Position, External Perimeters First |
| 06/09/21 | Print / 0.55 QUALITY - Output | Check Verbose G-code |