# Test Plans for STM32F4DISCOVERY

Example firmware and test plan targeting SiLabs *EFM32WG-STK3800 EFM32 Wonder Gecko Starter Kit*.

- `STK3800_blink.hex` : Example "blink" firmware for STK3800
- `suite-efm32-blink.yaml` : PLT test plan for `STK_blink.hex`
- `STK3800_blink_fast.hex` : Example "blink" firmware for STK3800 (fast blink)
- `suite-efm32-blink-fast.yaml` : PLT test plan for `STK3800_blink_fast.hex`

## Connection

To connect the EFM32WG-STK3800 to the PLT, connect the following signals from the
Debug Connector (DBG):

| Pin | Signal       | PLT Signal   |
|-----|--------------|--------------|
| 2   | `SWDIO`      | `SWD_SWDIO`  |
| 3   | `GND`        | `GND`        |
| 4   | `SWCLK`      | `SWD_SWCLK`  |
| 9   | Cable Detect | `GND`        |
| 10  | `RESET`      | `SWD_NRST`   |

Use Simplicity Studio to set the "Debug IN" debug mode on the board controller.
Power the starter kit board through mini-USB while programming from the PLT.
