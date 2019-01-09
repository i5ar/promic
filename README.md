# Promic

KiCad library (footprint and symbol) interfacing Pro Micro compatible boards.

Compatible boards:
- [Sparkfun Pro Micro](https://www.sparkfun.com/products/12640);
- [QMK Proton C](https://olkb.com/parts/qmk-proton-c);
- Elite-C.

![pinout](https://github.com/i5ar/pro-micro/blob/master/pinout.png?raw=true)

## Pinout

Based on [Dev-12640](https://cdn.sparkfun.com/datasheets/Dev/Arduino/Boards/ProMicro16MHzv1.pdf).

| Left       | Right       |
|------------|-------------|
| TXO/D1     | **RAW**     |
| RXI/D0     | **GND**     |
| **GND**    | **RST**     |
| **GND**    | **VCC**     |
| SDA/D2     | A3          |
| SCL/D3 (~) | A2          |
| D4/A6      | A1          |
| D5  (~)    | A0          |
| D6/A7 (~)  | D15         |
| D7         | D14         |
| D8/A8      | D16         |
| D9/A9 (~)  | D10/A10 (~) |

## Contribution

> **Branches** are one honking great idea -- let's do more of those!
