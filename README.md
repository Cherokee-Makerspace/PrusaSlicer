# PrusaSlicer Configuration Bundle
for Cherokee Makerspace 3D Printers

This bundle has been tested on [PrusaSlicer](https://www.prusa3d.com/prusaslicer/) V2.3.0
It is for [Cherokee Makerspace 3D Printers Only]

To use, select Import Config Bundle from the Prusa Slicer File / Import menu.

## Printers Supported

| Printer | Nozzle | Bed Size | G-Code | Host Type |
| ------- | ------ | -------- | ------ | --------- |
| Prusa i3 Mk2.5s | 0.4 Steel | 250x210x210 | Marlin | OctoPrint |
| Prusa i3 Mk3s MMU2s | 0.4 Brass | 250x210x210 | Marlin | OctoPrint |
| [Robo 3D R1](https://github.com/Cherokee-Makerspace/Robo-Garolite.git) | 0.8 Steel | 220x200x200 | Marlin | OctoPrint |
| [Robo 3D R1+](https://github.com/Cherokee-Makerspace/Robo-Buildtak.git) | 0.8 Steel | 220x200x200 | Marlin | OctoPrint |
| [Cube Pro](https://github.com/Cherokee-Makerspace/Duet-Cube.git) | 0.4 Vanadium | x | RepRap Firmware | Duet |

### Print Settings

| Section | Setting | Notes |
| ------- | ------- | ----- |
| Output Options | Verbose G-Code | [x] |
| Output Options | Output filename format |  {input_filename_base}_{layer_height}_{filament_type[0]}_{printer_model}_{print_time}.gcode |

| Setting | LH | 1LH | #P | TL | BL | Infill | Pattern |
| ------- | -- | --- | -- | -- | -- | ------ | ------- |
| 0.35 INSANE | 0.35 | 0.2 | 2 | 3 | 3 | 10% | Cubic |

| Speeds | Per | SmP | ExP | Infl | SInf | TInf | Sprt | Brdg | Gap | Trav | 1Lyr |
| ------ | --- | --- | --- | ---- | ---- | ---- | ---- | ---- | --- | ---- | ---- |
| 0.35 INSANE | 100 | 50 | 70 | 250 | 250 | 100 | 100 | 60 | 80 | 180 | 30 |
 
### Filament Settings

| Filament | Nozzle | Bed |
| -------- | ------ | --- |
| Inland PLA | 210 / 205 | 60 / 60 |
| Inland PETG | 230 / 230 | 85 / 80 |

### Changelog

| Date | Setting | Notes |
| ---- | ------- | ----- |
| 06/18/21 | Printer | Switched all printers to wired Ethernet IP |
| 06/09/21 | Printer | Removed Robo 3D (0.4) since both Robos are now using 0.8 Nozzles  |
| 06/09/21 | Print / 0.55 DRAFT - Layers | 3 Perimeters, Avoid Crossing Perimeters, External Perimeters First, Nearest Seam Position, External Perimeters First |
| 06/09/21 | Print / 0.55 DRAFT - Infill | 15% Infill, 2.5 Infill Anchor, 10mm Max Infill Anchor |
| 06/09/21 | Print / 0.55 DRAFT - Output | Check Verbose G-code |
| 06/09/21 | Print / 0.40 QUALITY - Layers | 3 Perimeters, Avoid Crossing Perimeters, External Perimeters First, Nearest Seam Position, External Perimeters First |
| 06/09/21 | Print / 0.55 QUALITY - Output | Check Verbose G-code |