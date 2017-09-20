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

## Ordering

The board is currently shared on [OSHPark][oshpark] and can be ordered.  The
cost is $9.95 (USD) with a turnaround time of approximately 15 calendar days.

The Olimex [iCE40HX8K][olimex-parts] evaluation board can be purchased
through [Olimex][olimex-fpga].


## LICENSE

These designs are licensed under the APACHE 2 license [LICENSE](LICENSE).

This design uses the [Olimex][olimex]  2x20 0.05" pitch SMD connectors from
their [KiCAD parts library][olimex-parts], which are also licensed under
APACHE 2.


[olimex]: https://www.olimex.com/
[olimex-fpga]: https://www.olimex.com/Products/FPGA/iCE40/iCE40HX8K-EVB/open-source-hardware
[olimex-parts]: https://github.com/OLIMEX/KiCAD
[oshpark]: https://oshpark.com/shared_projects/dG68p194
