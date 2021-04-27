# Test Plans for LPCXpresso 11C24

Example firmware and test plan targeting NXP's *LPC11C24 LPCXpresso devboard*.

- `suite-lpc11c24-sample.yaml` : PLT test plan for `blinky.hex`
- `suite-lpc11c24-sample-cmsis.yaml`: PLT test plan for `blinky.hex`, using external CMSIS-DAP programmer.
    Requires `Keil.LPC1100_DFP.1.4.0.pack`, available from [Keil](https://www.keil.com/dd2/pack/)
- `blinky.hex` : Example "blinky" firmware for LPC11C24
- `suite-lpc11c24-sample-200ms.yaml` : PLT test plan for `blink-200ms.hex`
- `blinky-200ms.hex` : Example "blinky" firmware for LPC11C24, with 200ms duty cycle
