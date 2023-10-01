# GraphicPlus

Parallel printer card for Apple II

This is a work in progress

A clone of Orange Micro's Grappler+ printer card, from their published schematic, with the known bugfixes of their later revisions applied.

Component values not specified on schematic:

* C2, C4, C5, C5 - bypass capactors, 100nF should be fine.
* C1, C3, C7, C8 - on photos I've seen, C1 is 100pF, C3 is 470pF, C7 is 100pF
* D1 - signal diode, 1n4148, 1n914, etc should be fine.

If you only want to use this as a firmware expansion card (i.e. for SoftSP), you can omit U5, U6, U10, U11, S1, D1, and J2.

Pins 2,4,6,8 of the port header are left unconnected for maximum compatibility with common PC parallel port IDC26F to DB25F dongles. If you need those pins to be connected to ground as in the original Grappler cards, short jumpers JP1,JP2,JP3,JP4.
