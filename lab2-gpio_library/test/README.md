# Lab 2: YOUR_FIRSTNAME LASTNAME

### GPIO control registers

1. Complete the table for DDRB and PORTB control register values.

   | **DDRB** | **PORTB** | **Direction** | **Internal pull-up resistor** | **Description** |
   | :-: | :-: | :-: | :-: | :-- |
   | 0 | 0 | input | no | Tri-state, high-impedance |
   | 0 | 1 | input | yes | Pxn will source current if ext.pulled low|
   | 1 | 0 | output | no | output Low (sink) |
   | 1 | 1 | output | no | output high (source) |

### GPIO library

2. Complete the table with code sizes from three versions of the blink application.

   | **Version** | **Size [B]** |
   | :-- | :-: |
   | Ver. 1: Arduino-style | 508 |
   | Ver. 2: Registers | 158 |
   | Ver. 3: Library functions | 150 |

### Traffic light

3. Scheme of traffic light application with one red/yellow/green light for cars, one red/green light for pedestrians, and one push button. Connect AVR device, LEDs, resistors, push button (for pedestrians), and supply voltage. The image can be drawn on a computer or by hand. Always name all components and their values!

![Scheme of traffic light application](https://raw.githubusercontent.com/MathisNickels/digital-electronics-2/main/lab2-gpio_library/test/image.png)   
