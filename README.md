# ZXBUS Kicad symbols and footprints

This is ZX Spectrum edge connector (ZX Bus) Kicad model. There are several popular bus variants, which are supported.

## ZX Spectrum 48/128 Edge Connector

This is initial edge connector, which exists in all ZX Spectrum machines. 

![ZX Spectrum 48 Edge Connector, CC-BY-NC-SA-3.0, by kio (http://k1.spdns.de)](https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/zx48.jpg)

In 128K versions some of the signals were removed (most notable is /IORQGE) and few were added (e.g., Disk RD/WR in +3). 
I haven't created separate schematic elements for this connectors since the 48K one may be used with minor limitations. 

Same footprint may be used for peripheral devices as well. In this case the SL-56 slot pins should be soldered 
like this on both sides of PCB:

![Betadisk-128 clone photo, CC-BY-SA-4.0, by KVPetr (Wikipedia)](https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/zx48-slot.jpg)
