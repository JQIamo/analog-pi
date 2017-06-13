# analog-pi
Analog PI controller with > 10MHz bandwidth. Design by Joe Tiamsuphat.

For full documentation of the circuit, see the [manual](https://github.com/JQIamo/analog-pi/blob/master/pi/Documents/PI_Manual.pdf).

## File description

* `/fab/*`: Ready-made files for immediate fabrication. There is the main PI board (`pi_v2.5.3`), and three "shield" boards which make assembly into the box (located in `/fab/EnclosureDesign_v2.5.3_CAD`) easier. See below for description.
* `/pi/*`: Design files for the main PI board, including documentation, schematics, simulations, etc. The schematic/board layout are done in NI Multisim + Ultiboard.
* `/pi-frontpanel/*`: Eagle board files for a frontpanel "shield" board
* `/pi-pots/*`: Eagle board files for potentiometers which set the gains, output offset, sweep amplitude.
* `/pi-shield/*`: Eagle board file for adapter shield between PI board and the POTs/Frontpanel breakout boards.

Total cost is in the neighborhood of $1k per completed box (includes professionally populated PCBs, enclosure, power supply, etc.), although that number would depend on quantity ordered, whether you populate the boards yourself, etc.

## Enclosure

There is a Protocase Designer file (in `/fab/EnclosureDesign_v2.5.3_CAD`

![enclosure](https://github.com/JQIamo/analog-pi/blob/master/fab/EnclosureDesign_v2.5.3_CAD/enclosure_screenshot.png)

Other auxiliary parts:

| Name | Part number | supplier |
|-------|------------|-------|
| FuseDrawer | 486-1342-ND | Digikey|
|Fuse	|F2393-ND|	Digikey|
|PwrEntry	|486-1302-ND	|Digikey
HexStandoff	|36-4802-ND|	Digikey
KnurledKnob	|226-3084-ND	|Digikey
POT Dial|	987-1002-ND	|Digikey
Isolated BNC	|ARFX1905-ND	|Digikey
PowerSupply	|179-2302-ND|	Digikey
