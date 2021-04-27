# Test Plans for STM32F4DISCOVERY

Example firmware and test plan targeting ST's *STM32F4 Discovery kit*.

- `zephyr-sample-blinky.hex`: Example "blinky" firmware for STM32F4DISCOVERY
- `suite-stm32f4_disco-sample.yaml`: PLT test plan for `zephyr-sample.hex`
- `zephyr-sample-blinky-200ms.hex`: "blinky" firmware for STM32F4DISCOVERY, with 200ms duty cycle
- `suite-stm32f4_disco-sample-200ms.yaml`: PLT test plan for `zephyr-sample-200ms.hex`
- `zephyr-sample-CAN.hex`: `samples/drivers/CAN` Zephyr sample firmware for STM32F4DISCOVERY 
- `suite-stm32f4_disco-sample-CAN.yaml` : PLT test plan for `zephyr-sample-CAN.hex`

## CAN Sample

To test CAN on the STM32F4 Discovery board, an external CAN transceiver, like 
Waveshare's [SN65HVD230](https://www.waveshare.com/sn65hvd230-can-board.htm), is required, and
should be hooked up to the Discovery board as follows:

| Transceiver   | STM32F4 Discovery |
|---------------|-------------------|
| 3.3V          | 3V                |
| GND           | GND               |
| CAN\_RX       | PB5               |
| CAN\_TX       | PB13              |

The `CAN_L` and `CAN_H` signals of the CAN transceiver can then be
connected to the `CAN_L` and `CAN_H` signals of the PLT.

## References

. [STM32F4DISCOVERY - STMicroelectronics](http://www.st.com/en/evaluation-tools/stm32f4discovery.html)

