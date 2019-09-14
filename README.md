# ZX-BUS Kicad symbols and footprints

This is ZX Spectrum edge connector (ZX Bus) Kicad model. There are several popular bus variants, which are supported.

## ZX Spectrum 48/128 Edge Connector

<img align="right" src="https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/symbol-zx.png" />
This is initial edge connector, which exists in all ZX Spectrum machines. 

![ZX Spectrum 48 Edge Connector, CC-BY-NC-SA-3.0, by kio (http://k1.spdns.de)](https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/zx48.jpg)

In 128K versions some of the signals were removed (most notable is /IORQGE) and few were added (e.g., Disk RD/WR in +3). 
I haven't created separate schematic elements for this connectors since the 48K one may still be used with minor limitations. 

Same footprint may be used for peripheral devices as well. In this case the SL-56 slot pins should be soldered 
like this on both sides of PCB:

![Betadisk-128 clone photo, CC-BY-SA-4.0, by KVPetr (Wikipedia)](https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/zx48-slot.jpg)

## NemoBus

<img align="right" src="https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/symbol-nemo.png" />
De-facto standard for Russian clones since late 90s. The first appearence of 62-pin option was Used in KAY-1024, however, 56-pin bus with almost the same signals was used in popular Scorpion ZS-256 computer. On the contrary to the original ZX Spectrum bus, the NemoBus is made as the slot (SL-62, ISA-8 form-factor).

![](http://speccy.info/w/images/1/18/P1024sl2_motherboard.jpg)

Extension devices contain edge connector. Since A31 and B31 are not connected (and most likely were added only because SL-62 slots are much more widespread than the SL-60), these pins are even absent in PCB sometimes: 

![ZX Multicard, Own work, CC-BY-SA-3.0](https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/zxmc.jpg)

## Quorum Bus

<img align="right" src="https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/symbol-quorum.png" />
The edge connector, which was used in Quorum clone. It is virtually the same as standard ZX Spectrum 48 edge connector, but signals like 12V and video are not connected. Implemented physically as edge connector, but the pins step is of Soviet standard (2.5 mm).

![](https://raw.githubusercontent.com/wiki/atsidaev/zxbus/images/quorum.jpg)

Also, it contains signals, which are specific for Quorum - e.g., UPS (Upper Screen, switch screen to 0xC000).
