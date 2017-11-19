GPD Pocket Internal USB HUB
===============

This is a modification gadget for GPD Pocket, which add three USB ports to maintain other original functions.
The addition is performed in a smart way by just replacing the original FPC between main and sub boards to this device.

# Gallery
## Implementation (Rev.A board, previous version)
<a href='https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/HUB_FPC_assembled_0.jpg'><img src='https://raw.githubusercontent.com/fenrir-naru/GPD_Pocket-mods/master/internal_usb_hub/HUB_FPC_assembled_0.jpg' width='400px' /></a>

<a href='https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/HUB_FPC_assembled_1.jpg'><img src='https://raw.githubusercontent.com/fenrir-naru/GPD_Pocket-mods/master/internal_usb_hub/HUB_FPC_assembled_1.jpg' width='400px' /></a>

## Before / after of device manager
Before: <a href='https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/HUB_FPC_before.png'><img src='https://raw.githubusercontent.com/fenrir-naru/GPD_Pocket-mods/master/internal_usb_hub/HUB_FPC_before.png' width='400px' /></a>

After: <a href='https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/HUB_FPC_after.png'><img src='https://raw.githubusercontent.com/fenrir-naru/GPD_Pocket-mods/master/internal_usb_hub/HUB_FPC_after.png' width='400px' /></a>

# Board
[EagleCAD](http://www.cadsoftusa.com/) files are available ([schematics](https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/HUB_FPC.sch) and [layout](https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/HUB_FPC.brd). The gerber files are also available in [zip format](https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/gerber.zip). Its components are listed in [BOM](https://github.com/fenrir-naru/GPD_Pocket-mods/tree/master/internal_usb_hub#bom-bill-of-material). The board design is published under [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/).

## BOM (bill of material)

<a href='https://github.com/fenrir-naru/GPD_Pocket-mods/blob/master/internal_usb_hub/HUB_FPC_brd.png'><img src='https://raw.githubusercontent.com/fenrir-naru/GPD_Pocket-mods/master/internal_usb_hub/HUB_FPC_brd.png' width='100%' /></a>

| **Part** | **Value** | **Package** | **Multiple** |
|:---------|:----------|:------------|:-------------|
| C1, C2 | 20p | 1005 | 2 |
| C3, C4, C5, C6, C7 | 0.1u / 10V | 1005 | 5 |
| CON1 | [Panasonic AXE610124](https://www.digikey.com/product-detail/en/panasonic-electric-works/AXE610124/255-3198-1-ND/2793931) | | 1 |
 | IC1 | [Cypress CY7C65632-28](https://www.digikey.com/product-detail/en/cypress-semiconductor-corp/CY7C65632-28LTXC/CY7C65632-28LTXC-ND/2805206) | QFN28 | 1 |
| R1 | 649 | 1005 | 1 |
| R2, R4 | 10K | 1005 | 2 |
| R3 | 100K | 1005 | 1 |
| XTAL1 | [Abracon ABM10-167](https://www.digikey.com/product-detail/en/abracon-llc/ABM10-167-12.000MHZ-T3/535-13521-1-ND/6140274) | 2520 | 1 |

# Additional information
* The project owner's website is [Fenrir's BLog](http://fenrir.naruoka.org/).
