# 🔌 Pin Assignment — STM32F103C8T6

## Key Matrix (20 pins)

| Function | GPIO | Notes |
|---|---|---|
| Row 0 | PA0 | Output (scan) |
| Row 1 | PA1 | Output |
| Row 2 | PA2 | Output |
| Row 3 | PA3 | Output |
| Row 4 | PA4 | Output |
| Col 0 | PB0 | Input (pull-up) |
| Col 1 | PB1 | Input |
| Col 2 | PB2 | Input |
| Col 3-14 | PB3–PB14 | Input |

## USB (2 pins)

| Function | GPIO |
|---|---|
| USB D- | PA11 |
| USB D+ | PA12 |

## RGB (1 pin, v0.2)

| Function | GPIO |
|---|---|
| WS2812B data | PA5 |

## Crystal

| Function | Pin |
|---|---|
| OSC_IN | Pin 5 |
| OSC_OUT | Pin 6 |

## QMK Config

```c
#define MATRIX_ROWS 5
#define MATRIX_COLS 15
#define MATRIX_ROW_PINS { A0, A1, A2, A3, A4 }
#define MATRIX_COL_PINS { B0, B1, B2, B3, B4, B5, B6, B7, B8, B9, B10, B11, B12, B13, B14 }
#define DIODE_DIRECTION COL2ROW
```

> Update this doc whenever pins change during PCB layout.
