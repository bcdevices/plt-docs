# Test plans for nRF52DK

Example project targeting Nordic's **nRF52 DK** development kit.

- [suite-hrs-BLE.yaml](suite-hrs-BLE.yaml)
- [nrf52832\_xxaa.hex](nrf52832_xxaa.hex): ble\_app\_hrs firmware (nRF52 SDK example
- `s132_nrf52_6.0.0_softdevice.hex` (Available from Nordic)

- [zephyr-sample-blinky.hex](zephyr-sample-blinky.hex): Example "blinky" firmware for nRF52DK
- [suite-nrf52\_pca10040-sample.yaml](suite-nrf52_pca10040-sample.yaml): PLT test plan for `zephyr-sample.hex`
- [zephyr-sample-blinky-200ms.hex](zephyr-sample-blinky-200ms.hex): "blinky" firmware for nRF52DK, with 200ms duty cycle
- [suite-nrf52\_pca10040-sample-200ms.yaml](suite-nrf52_pca10040-sample-200ms.yaml): PLT test plan for `zephyr-sample-200ms.hex`


## PLT-200A connection

Use a USB 2.0 Type-A to micro-USB cable to connect the nRF52DK micro-USB port to any of the
USB ports in the back of the PLT-200A.

## References

- [nRF52 DK development kit for Bluetooth Low Energy, Bluetooth 5, ANT, 2.4GHz and NFC, supporting the nRF52 Series - nordicsemi.com](https://www.nordicsemi.com/Software-and-Tools/Development-Kits/nRF52-DK)
