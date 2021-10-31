# PrusaSlicer Configuration Bundle
for Cherokee Makerspace 3D Printers

## Installation
Download and install the latest version of [PrusaSlicer](https://www.prusa3d.com/prusaslicer/)
In the Prusa Slicer Configuration Assistant, check the following:
1. Original Prusa i3 MK3s MMU2s (0.4 nozzle)
2. Original Prusa i3 MK2.5S (0.4 nozzle)

## Starting Over
1. Run Configuration Assistant from the Configuration menu.
2. Check - Remove User Profiles

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
| BASF Ultrafuse | 230 / 225 | 95 / 90 |