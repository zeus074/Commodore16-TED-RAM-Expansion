# Commodore16-TED-RAM-Expansion
64Kb RAM solderless expansion for Commodore 16/116

Adapter to put under the TED to be able to expand the computer memory.
You can simply disable it by insert jumper J1

The schematic and gerber are in the PCB folder.
You can pickup printed circuit on PCBWAY: https://www.pcbway.com/project/shareproject/Commodore_16_RAM_expansion_64Kb_solderless_on_TED_514ba3fc.html

Test video: https://youtu.be/bT41rbG4aQM

*Please consider subscribing to the channel*

3D view:

![alt text](https://github.com/zeus074/Commodore16-TED-RAM-Expansion/blob/main/IMG/3d_expansion.jpg)

**Components:**

R1: 10K 0805

C1,C2,C3: 100nF 10v 0805

U2: 48pin socket for TED (or 2 female 24pin strips 2.54)

U3: SRAM CY62128EV30LL-45ZAXIT (STSOP-32)

U4: SN74HCT00PWR (TSSOP-14)

U5: 74HCT1G32GV,125 (SC-74A-5)

Socket: 2 male 24pin turned strips 2.54

J1: HDR male 2.54 1x2 (2 pins male strip) + jumper key

PCB view:

![alt text](https://github.com/zeus074/Commodore16-TED-RAM-Expansion/blob/main/IMG/Expansion.jpg)

**Installation:**

The installation of the adapter is simple, just remove the TED and insert the adapter in its place and finally insert the TED on top.
Pay attention to the orientation of the adapter and the TED.
The pins of the C16 socket could widen and be no longer usable without the adapter.
In this case it is necessary to use a turned socket or insert an additional socket between the adapter and the commodore socket.

**Usage:**

Double check that you have inserted everything in the correct direction!.
Turn on the computer with the J1 jumper open; the computer will start with 64kb.
If you turn on the computer with the jumper inserted, expansion will be disabled and system memory will be used.