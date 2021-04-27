# Test Plans for Atmel AVR ATmega168P/PB

Example firmware and PLT test plans for Microchip's
**ATmega168PB Xplained Mini** evaluation kit.

- [8led\_1hz.hex](8led_1hz.hex): Example firmware for ATmega168P/PB
- [atmega168pb-XPmini-erase.yaml](atmega168pb-XPmini-erase.yaml): Test plan to erase ATmega168PB Xplained Mini DevKit
- [atmega168pb-XPmini-program.yaml](atmega168pb-XPmini-program.yaml): Test plan to program ATmega168PB Xplained Mini DevKit
- [atmega168pb-erase.yaml](atmega168pb-erase.yaml): Test plan to erase ATmega168PB
- [atmega168pb-program.yaml](atmega168pb-program.yaml): Test plan to program ATmega168PB

## PLT-200A connection

For the [atmega168pb-XPmini-erase.yaml](atmega168pb-XPmini-erase.yaml) and
[atmega168pb-XPmini-program.yaml](atmega168pb-XPmini-program.yaml) test plans, hook
up the Xplained Mini micro-USB port to any of the USB ports in the back of the PLT-200A.

To program the ATmega168P/PB over ISP, as in the [atmega168pb-erase.yaml](atmega168pb-erase.yaml) and
[atmega168pb-program.yaml](atmega168pb-program.yaml) test plans, connect the PLT-200A JTAG signals to
the ATmega168 as below:

| PLT-200A JTAG pin | PLT-200A  Signal | AVR Function | ISP Pin | AVR Pin |
|:-----------------:|------------------|--------------|:-------:|---------|
| 1                 | JTAG\_VCC        | VCC          | 2       | Vcc     |
| 2                 | JTAG\_TMS        | RESET        | 5       | PC6     |
| 3                 | GND              | GND          | 6       | GND     |
| 4                 | JTAG\_TCK        | SCK          | 3       | PB5     |
| 6                 | JTAG\_TDO        | MISO         | 1       | PB4     |
| 8                 | JTAG\_TDI        | MOSI         | 4       | PB3     |

## References

- [Microchip Technology: ATmega168PB Xplained Mini](https://www.microchip.com/DevelopmentTools/ProductDetails/PartNO/ATMEGA168PB-XMINI)
