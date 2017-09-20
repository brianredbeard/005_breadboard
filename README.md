# 005 Breadboard Breakout

## About

This is a breakout board for 0.05" (1.27mm) pitch parts so that they may be
connected to a standard 0.1" (2.54mm) pitch breadboard.

It was originally designed for use with the [Olimex iCE40HX8K-EVB][olimex-fpga].
This board uses a series of 40 pin IDC cables with 0.05" pitch which is great
from the perspective of maximizing the footprint of the development board...
it's sub-optimal for any peripheral development.  Additionally, this board
should be usable for other projects with similar footprint needs.


## Files


```
├── 005_breadboard-cache.lib          - a local copy of symbols used in the schematic
├── 005_breadboard.kicad_pcb          - kicad pcb layout file
├── 005_breadboard.pro                - project file (parameters for project)
├── 005_breadboard.sch                - kicad schematic file
├── 005_breadboard_schematic.pdf      - rendering of schematic in PDF
├── 005_breadboard_top.png            - 3d screenshot of board top
├── 005_breadboard_bottom.png         - 3d screenshot of board bottom
├── gerbers                           - gerber files for manufacturing
│   ├── 005_breadboard-B.Cu.gbl
│   ├── 005_breadboard-B.Mask.gbs
│   ├── 005_breadboard-B.SilkS.gbo
│   ├── 005_breadboard.drl
│   ├── 005_breadboard-Edge.Cuts.gm1
│   ├── 005_breadboard-F.Cu.gtl
│   ├── 005_breadboard-F.Mask.gts
│   └── 005_breadboard-F.SilkS.gto
└── .pretty                           - folder of local project footprints
```

## Screenshots

Top of board:

![Top of board](/005_breadboard_top.png?raw=true "Board Top")


Bottom of board:

![Bottom of board](/005_breadboard_bottom.png?raw=true "Board Bottom")

## Schematic

A simple PDF of the schematic can be downloaded [here](/005_breadboard_schematic.pdf)


## Bill of Materials

To build this board you will need the following:

| Part # | Quantity | Description |
| --     | --       | --          |
| 2x20 Pin Header | 1 | 2x20 0.05" (1.27mm) Pin header (male or female depending on need) |
| 1x20 Pin header (male) | 2  | 2x20 0.1" (2.54mm) Pin header (male) to be connected to breadboard |

The 0.05" pin headers can be sourced from a number of locations:

  - Olimex  - [female][olimex-ph5-f] / [male][olimex-ph5-m] 
  - Digikey - [female][digikey-ph5-f] / [male][digikey-ph5-m] 

The 0.10" pin headers can be sourced from a number of locations:

  - Digikey - [female][digikey-ph10-f] / [male][digikey-ph10-m] 

## Ordering

The board is currently shared on [OSHPark][oshpark] and can be ordered.  The
cost is $9.95 (USD) with a turnaround time of approximately 15 calendar days.

The Olimex [iCE40HX8K][olimex-fpga-source] evaluation board can be purchased
through [Olimex][olimex-fpga].


## LICENSE

These designs are licensed under the APACHE 2 license [LICENSE](LICENSE).

This design uses the [Olimex][olimex]  2x20 0.05" pitch SMD connectors from
their [KiCAD parts library][olimex-parts], which are also licensed under
APACHE 2.


[olimex]: https://www.olimex.com/
[olimex-fpga]: https://www.olimex.com/Products/FPGA/iCE40/iCE40HX8K-EVB/open-source-hardware
[olimex-fpga-source]: https://github.com/OLIMEX/iCE40HX8K-EVB
[olimex-parts]: https://github.com/OLIMEX/KiCAD
[oshpark]: https://oshpark.com/shared_projects/dG68p194

[olimex-ph5-f]: https://www.olimex.com/Products/Components/Connectors/FEMALE-YAV36P-2x05/
[olimex-ph5-m]: https://www.olimex.com/Products/Components/Connectors/MALE-PAV16X-2x05/

[digikey-ph5-f]: https://www.digikey.com/product-detail/en/amphenol-fci/20021321-00040T4LF/609-3779-ND/2209124
[digikey-ph5-m]: https://www.digikey.com/product-detail/en/harwin-inc/M50-3602042/952-1393-ND/2264374
[digikey-ph10-f]: https://www.digikey.com/product-detail/en/sullins-connector-solutions/PPPC201LFBN-RC/S7053-ND/810192
[digikey-ph10-m]: https://www.digikey.com/product-detail/en/sullins-connector-solutions/PRPC020SAAN-RC/S1011EC-20-ND/2775234
