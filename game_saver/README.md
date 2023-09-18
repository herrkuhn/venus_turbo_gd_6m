# Game Saver

Some notes on the Venus Turbo Game Doctor 4+ Game Saver

Top PCB:  
<img alt="" src="images/game_saver_pcb_top.jpg?raw=true" width="400" target="blank"> <img alt="" src="images/game_saver_pcb_top_blank.jpg?raw=true" width="400" target="blank">

Bottom PCB:  
<img alt="" src="images/game_saver_pcb_bottom.jpg?raw=true" width="400" target="blank"> <img alt="" src="images/game_saver_pcb_bottom_blank.jpg?raw=true" width="400" target="blank">

## ICs

| Board # | IC                     | Socket | Function                                           | Datasheet                               |
|:--------|:-----------------------|:------:|:---------------------------------------------------|:----------------------------------------|
| U1      | -B9048 / GAL16V8-25LNC |   Y    | Generic Array Logic                                | [Link](../datasheets/GAL16V8-25LNC.pdf) |
| U2      | 791B0 / M74HC174P      |        | Hex D-Type flip flop with common clock and reset   | [Link](datasheets/M74HC174P.pdf)        |
| U3      | -B9048 / GAL16V8-25LNC |   Y    | Generic Array Logic                                | [Link](../datasheets/GAL16V8-25LNC.pdf) |
| U4      | I09 / GD74HC74         |        | Dual D-Type flip flop with preset and clear        | [Link](datasheets/GD74HC74.pdf)         |
| U5      | 8841-DS / UM6116-3     |        | 2Kx8 High Speed CMOS SRAM                          | [Link](datasheets/UM6116.pdf)           |
| U6      | M74HC153F1 / 88732     |        | Dual 4-input multiplexer                           | [Link](datasheets/74HC153.pdf)          |
| U7      | M74HC161F1 / 88732     |        | Synchronous Binary Counter with Asynchronous Clear | [Link](datasheets/74HC161.pdf)          |
| U8      | M74HC153F1 / 88732     |        | Dual 4-input multiplexer                           | [Link](datasheets/74HC153.pdf)          |
| U9      | M74HC161F1 / 88732     |        | Synchronous Binary Counter with Asynchronous Clear | [Link](datasheets/74HC161.pdf)          |
| U10     | M74HC32FI / 88809      |        | Quad 2-input OR Gate                               | [Link](datasheets/M74HC32.pdf)          |
| U11     | M74HC153F1 / 88732     |        | Dual 4-input multiplexer                           | [Link](datasheets/74HC153.pdf)          |
| U12     | M74HC161F1 / 88732     |        | Synchronous Binary Counter with Asynchronous Clear | [Link](datasheets/74HC161.pdf)          |
| U13     | M5L2764K / 8412AN      |   Y    | 65536-Bit (8192-Word by 8-Bit) EEPROM              | [Link](datasheets/M5L2764K.pdf)         |

Dump of U13/M5L2764K content [here](firmware/venus_game_saver_M5L2764K_e1cfe03e.bin).

## Resistors

| Board # | Rings                  |        Value |
|:--------|:-----------------------|-------------:|
| R1      | green-blue-yellow-gold |  560k Ohms 5% |

## Capacitors

| Board # | Mark  |    Value |
|:--------|:------|---------:|
| C1      | empty |          |
| C2      | N/A   |          |
| C3      | 104   |    100nF |
| C4      | empty |          |
| C5      | empty |          |
| C6      | 104   |    100nF |
| C7      | empty |          |
| C8      | 104   |    100nF |
| C9      | 104   |    100nF |
| C10     | empty |          |
| C11     | empty |          |
| C12     | 104   |    100nF |
| C13     | empty |          |
| C14     | empty |          |
| C15     |       | 22uF 25V |
| C16     |       | 22uF 25V |
| C17     | 104   |    100nF |

## Diodes

| Board # | Type   |
|:--------|:-------|
| D1      | 1N4148 |
| D2      | 1N4148 |
