# radio-keychain
A fully-functional FM receiver in a 3x3cm footprint, perfect for a keychain.

It uses the connected headphones as an antenna, and is powered off a CR2032 coin cell. The FM tuner used is the Si4702, which supports the 76-108MHz frequency range.

Based on the CH32v003, this radio runs on RISC-V!

## Motivation
I love radio, and I wanted to make the tiniest keychain radio possible. I also thought it would be interesting to learn how radios work.

## How to use
First, connect a pair of headphones or an aux cable, this is your antenna. There are 4 buttons on the device, a volume up/down, and a frequency up/down. First, set the volume to a confortable level, and then use the frequency up/down buttons to step up and down 0.1MHz until you find a station. Then, enjoy listening to the station!

## Schematic and PCB
https://kicanvas.org/?repo=https://github.com/alx-alexpark/radio-keychain

## Zine
<img width="420" height="595" alt="A5 - 1" src="https://github.com/user-attachments/assets/6421719e-cac6-41cb-b35e-82c9e8a307f3" />

## Bill of Materials

| Designator | Footprint | Quantity | Value | LCSC Part # |
|---|---|---|---|---|
| BT1 | BAT-SMD_MY-2032-12 | 1 | MY-2032-12 | [C964833](https://www.lcsc.com/product-detail/C964833.html) |
| C1, C6 | 0402 | 2 | 100nF | [C1525](https://www.lcsc.com/product-detail/C1525.html) |
| C2 | 0402 | 1 | 100pF | [C1546](https://www.lcsc.com/product-detail/C1546.html) |
| C3, C4 | 0603 | 2 | 0.47uF | [C1623](https://www.lcsc.com/product-detail/C1623.html) |
| C5, C7, C8 | 0603 | 3 | 1uF | [C1592](https://www.lcsc.com/product-detail/C1592.html) |
| C9 | 0402 | 1 | 22nF | [C1532](https://www.lcsc.com/product-detail/C1532.html) |
| CN1 | PJ-320D | 1 | PJ-320D | [C431535](https://www.lcsc.com/product-detail/C431535.html) |
| D1 | 0402 | 1 | LED | [C2286](https://www.lcsc.com/product-detail/C2286.html) |
| FB1, FB2 | 0603 | 2 | BLM18BD252SN1D | [C77668](https://www.lcsc.com/product-detail/C77668.html) |
| J1 | PinHeader_1x03_P2.54mm_Vertical | 1 | Conn_01x03_Pin | — |
| L1 | 0603 | 1 | LQW18ANR27J00D | [C98093](https://www.lcsc.com/product-detail/C98093.html) |
| OSC1 | CRYSTAL-SMD_4P-L3.2-W2.5-BL | 1 | SX2M32_768KM20F30TNN | [C2901603](https://www.lcsc.com/product-detail/C2901603.html) |
| R1, R2, R3, R4, R5, R6 | 0603 | 6 | 10k | [C25804](https://www.lcsc.com/product-detail/C25804.html) |
| R10, R9 | 0402 | 2 | 2k | [C4109](https://www.lcsc.com/product-detail/C4109.html) |
| R11 | 0402 | 1 | 330 | [C25104](https://www.lcsc.com/product-detail/C25104.html) |
| R7, R8 | 0402 | 2 | 2.2k | [C25879](https://www.lcsc.com/product-detail/C25879.html) |
| SW1, SW2, SW3, SW4 | SW-SMD_4P-L4.2-W3.3-P2.15-LS5.1 | 4 | SW_Push_45deg | [C455282](https://www.lcsc.com/product-detail/C455282.html) |
| SW5 | SW-SMD_MST22D18G2 | 1 | K3-2235S-F1 | [C223858](https://www.lcsc.com/product-detail/C223858.html) |
| U1 | QFN-20-1EP_3x3mm_P0.4mm_EP1.65x1.65mm | 1 | CH32V003F4U6 | [C5299908](https://www.lcsc.com/product-detail/C5299908.html) |
| U2 | QFN-28_4x4mm_P0.5mm | 1 | TPA6130A2RTJR | [C130046](https://www.lcsc.com/product-detail/C130046.html) |
| U3 | MPS_QFN-16_3x3mm_P0.5mm | 1 | SI4702-C19-GMR | [C2155666](https://www.lcsc.com/product-detail/C2155666.html) |

