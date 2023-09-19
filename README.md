# GraphicPlus

Parallel printer card for Apple II

A clone of Orange Micro's Grappler+ printer card, from their published schematic, with the known bugfixes of their later revisions applied.

Component values not specified on schematic:

* C2, C4, C5, C5 - bypass capactors, 100nF should be fine.
* C1, C3, C7, C8 - on photos I've seen, C1 is 100pF, C3 is 470pF, C7 is 100pF
* D1 - signal diode, 1n4148, 1n914, etc should be fine.

If you only want to use this as a firmware expansion card (i.e. for SoftSP), you can omit U5, U6, U10, U11, SW1, D1, and J2.
