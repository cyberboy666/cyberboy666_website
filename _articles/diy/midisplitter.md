---
type: diy
layout: page
---

# 1 to 5 active midi splitter

i want a midi splitter so i can control/swap out different drum machines and synth sounds sequenced by the deluge.

this [blog] has an inspiring / informative write up of designing and building a splitter. i want to follow its design more or less (powering with 9v, building the circuit on perf board etc ). some differences from Daves project:
- i want to design a case to be 3d printed in fusion3D
- i want to use standard 'barrel plug' power sockets

## buying parts

i already have a few of the parts required to make this (a few resistors / capacitors, switches, leds , power sockets etc), however it seems that quite a lot of the missing parts are quite common composites. when shopping around for these common parts, i decided it would be better to stock up on a variety of common parts (capacitors, resistors, diodes) rather than buying single units or excessive amounts of the exact same part.
for this reason pricing this total project is difficult since i might use 1 electro capacitor from a pack of 120 i bought for it, for example. i will list the parts/variety packs that i did get and their prices here:

REFERENCE | PART	DESCRIPTION | PART	QTY | SET BOUGHT | PRICE (USD)
--- | --- | --- | --- | ---
 C1 |	Capacitor, electrolytic, 47uF |	1 | electro assort : 10x 1UF 2.2UF 3.3UF 4.7UF 10UF 22UF 33UF 47UF 100UF 220UF 330UF 470UF | 1.8 
C2, C3, C4 |	Capacitor, ceramic, 0.1uF |	3
D1, D2, D3 |	Diode, 1N4004 |	3 | assort diodes : 10x 1N914 1N4148 1N5819 1N4001 1N4002 1N4003 1N4004 1N4005 1N4007 | 1.69
D4 |	Diode, 1N4148 |	1 | see above | n/a
G1 |	9v battery clip |	1 | think i got one somewhere | n/a
IC1 |	Voltage regulator, 7805T |	1 | 10x 7805 | 0.8
IC2 |	Opto-isolator, 6N136 |	1 | 5x 6N136 | 1.79
IC3 |	Hex inverter, 74HC14N |	1 | 10x 74HC14 | 1
J1, J2 |DC power	Jack 2.1, switched |	2 | in stock | n/a
JP1, JP2, JP3, JP4, JP5 |	DuPont Header, 2-pin male |	5 | 3x 40pin female + 10x 40pin male | 0.82 + 0.5
JP6, JP7, JP8, JP9, JP10 |	DuPont Header, 3-pin male	| 5 | covered above | n/a
LED1, LED2 |	LED, 5mm, green |	2 | in stock | n/a
Q1 |	NPN Transistor, 2N3904 |	1 | transistor assort : 10x S9012 S9013 S9014 9015 9018 A1015 C1815 A42 A92 2N5401 2N5551 A733 C945 S8050 S8550 2N3906 2N3904 | 1.75
R1, R3, R5	| Resistor, 10K |	3 | assort resistors : 10x 10Ω 22Ω 47Ω 100Ω 150Ω 200Ω 220Ω 270Ω 330Ω 470Ω 510Ω 680Ω 1KΩ 2KΩ 2.2KΩ 3.3KΩ 4.7KΩ 5.1KΩ 6.8KΩ 10KΩ 20KΩ 47KΩ 51KΩ 68KΩ 100KΩ 220KΩ 300KΩ 470KΩ 680KΩ 1MΩ | 1.69
R2, R4, R6, R7, R8, R9, R10, R11, R12, R13, R14, R15 |	Resistor, 220R |	12 | see above | n/a
 S1 |	Toggle switch, on/off |	1
X1, X2, X3, X4, X5, X6 |	DIN socket, 5-pin |	6 | 10x 5 PIN DIN Panel Mount | 7.14

which is a total price of : $19 USD or (~$27)

still cheaper  than buying a midi splitter and a whole heap of spare parts for future projects !

- i may need to buy a larger piece of perf board depending on how i decide to lay out the case

## next steps

- i would quite like to try and understand the circuit a bit better : perhaps try a schematic drawing software and the perf drawing software
- designing the case in fusion3D (once measuring tool arrives)
- (once parts arrive) start putting it together !

## further midi tools :

- building the mutable instruments [midipal] would be a fun project !

[blog]: (https://moroccodave.com/2017/02/06/diy-midi-thru-box/)
[midipal]: https://mutable-instruments.net/archive/midipal/build/
