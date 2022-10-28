# Test Plans for STM32 NUCLEO-H753ZI

Example firmware and test plan targeting ST's *Nucleo H753ZI* development board.

- `nucleo_h753-dfu.yaml`: PLT test plan for programming NUCLEO-H753 using USB DFU.
  * Note: This plan requires the NUCLEO-H753 to be put into its ROM-based bootloader. One way to do this is to pull the BOOT0 pin to 3v3. Then, the `User USB` port (CN13) on the NUCLEO-H753 needs to be connected to the DUT USB-C port on the rear of the PLT-300. Finally, the NUCLEO-H753 needs to be powered by connecting its `USB PWR` port (CN1) to another PLT port.

- `nucleo_h753-stlink.yaml`: PLT test plan for programming NUCLEO-H753 using its built-in ST-Link interface.
- `nucleo_h753-swd.yaml`: PLT test plan for programming NUCLEO-H753 using PLT's SWD interface.
- `zephyr-nucleo_h753zi-blinky-3.2.0.hex`: Example "blinky" firmware for nucleo\_h753zi
- `zephyr-nucleo_h753zi-blinky-3.2.0.dfu`: Example "blinky" firmware for nucleo\_h753zi, in .dfu format.

## References

. [ST's NUCLEO-H753 Page](https://www.st.com/en/evaluation-tools/nucleo-h753zi.html)
. [Zephyr NUCLEO-H753 Page](https://docs.zephyrproject.org/latest/boards/arm/nucleo_h753zi/doc/index.html)
