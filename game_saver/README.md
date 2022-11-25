# Game Saver

Some notes on the Venus Turbo Game Doctor 4+ Game Saver

Top PCB:  
<img alt="" src="images/turbo_gd_6m_pcb_top.jpg?raw=true" width="400">

Bottom PCB:  
<img alt="" src="images/turbo_gd_6m_pcb_bottom.jpg?raw=true" width="400">

## ICs

|Board #|IC|Socket|Function| Datasheet                            |
|:---|:---|:---|:---|:-------------------------------------|
|U1|KM44C256BP-8 / 110 Korea|Y|256Kx4 Bit CMOS Dynamic RAM| [Link](datasheets/KM44C256BP.pdf)    |
|U2|CD74HC157E / H 9045||Quad 2-Input Multiplexer|[Link](datasheets/CD74HC157E.pdf)|
|U3|-B9118 / GAL16V8-25LNC|Y|Generic Array Logic| [Link](datasheets/GAL16V8-25LNC.pdf) |
|U4|KM44C256BP-8 / 102 Korea|Y|256Kx4 Bit CMOS Dynamic RAM| [Link](datasheets/KM44C256BP.pdf)    |
|U5|CD74HC157E / H 9045||Quad 2-Input Multiplexer|[Link](datasheets/CD74HC157E.pdf)|
|U6|SN74LS670N / XXEZ9114||4x4 Register File with 3-state outputs|[Link](datasheets/SN74LS670N.pdf)|
|U7|LB9042 / NMC27C64Q / 200|Y|64K EPROM| [Link](datasheets/NMC27C64Q.pdf)     |
|U8|-B9118 / GAL16V8-25LNC|Y|Generic Array Logic| [Link](datasheets/GAL16V8-25LNC.pdf) |
|U9|SN74LS670N / XXEZ9114||4x4 Register File with 3-state outputs|[Link](datasheets/SN74LS670N.pdf)|
|U10|SN74LS260N / KKBI9031||Dual 5-Input NOR Gate|[Link](datasheets/SN74LS260N.pdf)|
|U11|P9012G / MM74HC244N / MC74HC244N||Octal 3-STATE Buffer|[Link](datasheets/MM74HC244N.pdf)|
|U12|P9048 / MM74HC20N / MC74HC20N||Dual 4-Input NAND Gate|[Link](datasheets/MM74HC20N.pdf)|
|U13|??? CPLD ???|Y|||
|U14|9033 / V53C104P10L|Y|256Kx4 Bit CMOS Dynamic RAM| [Link](datasheets/V53C104P10L.pdf)   |
|U15|KM44C256BP-8 / 102 Korea|Y|256Kx4 Bit CMOS Dynamic RAM| [Link](datasheets/KM44C256BP.pdf)    |
|U16|KM44C256BP-8 / 102 Korea|Y|256Kx4 Bit CMOS Dynamic RAM| [Link](datasheets/KM44C256BP.pdf)    |
|U17|9033 / V53C104P10L|Y|256Kx4 Bit CMOS Dynamic RAM| [Link](datasheets/V53C104P10L.pdf)   |

Dump of U7/NMC27C64Q content [here](firmware/venus_turbo_gd_6m_NMC27C64Q_a9ac5513.bin).

## Transistors

|Board #|Mark|Type| Datasheet                     |
|:---|:---|:---|:------------------------------|
|Q1|113 23 112 2N 3904|2N3904 TO-92| [Link](datasheets/2N3904.pdf) |
|Q2|113 23 112 2N 3904|2N3904 TO-92| [Link](datasheets/2N3904.pdf) |

## Resistors

|Board #|Rings|        Value |
|:---|:---|-------------:|
|R1|green-blue-brown-gold|  560 Ohms 5% |
|R2|brown-black-yellow-gold| 100k Ohms 5% |
|R3|empty||
|R4|brown-black-orange-gold|  10k Ohms 5% |
|R5|green-blue-brown-gold|  560 Ohms 5% |
|R6|grey-red-orange-gold|  82k Ohms 5% |
|R7|brown-black-brown-gold|  100 Ohms 5% |
|R8|grey-red-orange-gold|  82k Ohms 5% |
|R9|green-blue-brown-gold|  560 Ohms 5% |
|R10|brown-black-red-gold|   1k Ohms 5% |
|R11|brown-black-yellow-gold| 100k Ohms 5% |
|R12|brown-black-yellow-gold| 100k Ohms 5% |
|R13|brown-black-red-gold|   1k Ohms 5% |

## Capacitors

|Board #|Mark| Value |
|:---|:---|------:|
|C1|103|  10nF |
|C2|103|  10nF |
|C3|103|  10nF |
|C4|103|  10nF |
|C5|103|  10nF |
|C6|471| 200nF |
|C7|empty||
|C8|10|  10pF |
|C9|10|  10pF |
|C10||2.2uF 50V|
|C11|103|  10nF |
|C12|103|  10nF |
|C13|103|  10nF |
|C14|103|  10nF |
|C15|103|  10nF |
|C16|empty||
|C17|empty||
|C18|empty||
|C19|103|  10nF |
|C20|10|  10pF |
|C21|10|  10pF |
|C22|103|  10nF |
|C23|103|  10nF |
|C24|103|  10nF |
|C25|103|  10nF |
|C26|20|  20pF ||
|C27|103|  10nF |
|C28||1000uF 16V|
|C29||33uF 16V|

## Diodes

|Board #| Type   |
|:---|:-------|
|D1| 1N4148 |
|D2| 1N4148 |
|D2| 1N4148 |

## Oscillators

|Board #|Mark|  Value |
|:---|:---|-------:|
|X1|KTS F24.000 MHz| 24 MHz |
|X2|CEI 20.00 MHz| 20 MHz |
