# POWER - MIX
an "Obelisk" style replacement for STS Serge systems/boats

Disclaimer: If you choose to use these files it is at your own risk! Don't mess with things if you don't know what you are doing! 

This is a simple processor style mixer with manual offset to replace an Obelisk power panel with something some may find more useful. 
Power distribution is via 3.96mm headers on the back so adapters have to be made from that style to the STS standard AMP connectors. 
(the vertical PCB mount AMP connectors are simply too big to use).

To make power harness adaptors:

FROM POW-MIX:
Wafer Connector 3.96mm 4 Pins SKU A-778 (tayda)
Crimp Terminal Connector 3.96mm SKU A-803 (tayda)
Housing Connector 3.96mm 4 Pins SKU A-796 (tayda)

TO STS SERGE: 
Female crimp socket 770146-1 (mouser, digikey)
Receptable M 7700751 (mouser, digikey)


| BOM                      |                                         |                                                                                             |
|--------------------------|-----------------------------------------|---------------------------------------------------------------------------------------------|
| C1                       | 22pF                                    | 0603 Capacitor                                                                              |
| C2, C3, C6, C7           | 100nF                                   | 0603 Capacitor                                                                              |
| C4, C5                   | 10uF                                    | THT Electrolytic cap (10mm max height)                                                      |
| IC1                      | TL072                                   | SOIC                                                                                        |
| IN1, IN2, IN3, OFFSET    | 50k-100k  ALFA style pot (Thonk, Tayda) |                                                                                             |
| R4, R5, R7, R8, R10, R13 | 100k                                    | 0603 Resistor                                                                               |
| R6                       | 240k                                    | 0603 Resistor                                                                               |
| R11, R12                 | 10R                                     | 1210 Resistor or fuse of your choosing (or just solder solid if you prefer life with SPICE) |
| R14                      | 330R                                    | 0603 Resistor                                                                               |

OTHER PARTS:
Designed for use with emerson johnson / cinch connectivity banana jacks. Part# 108-09XX-001. 

Uses 3.96mm 4 Pin power connectors (Tayda  SKU A-778)

Whatever you prefer as mezzanine connectors between front and rear PCB boards. (check the pin headers section for break-away styles at tayda.)  

The panel PCB for this contains a number of components that sit at different heights. The body of a banana jack is about 12 mm before the metal tab. 
I prefer to use the combination of a 10mm mf spacer (tayda SKU A-1265) with a 2mm insulation bushing (tayda SKU A-1436) between panel and panel PCB and then a 10mm ff spacer (tayda SKU A-1242). You'll need some M3 screws as well (tayda SKU A-1250).





