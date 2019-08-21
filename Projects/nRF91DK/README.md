# Test plans for nRF52DK

Example project targeting Nordic's **nRF91 DK** development kit.

- [nrf52832\_xxaa.hex](nrf52832_xxaa.hex): ble\_app\_hrs firmware (nRF52 SDK example
- [at\_client-JLink.yaml](at_client-JLink.yaml): PLT test plan to program nRF91 DK via USB (JLink)
- [at\_client-SWD.yaml](at_client-SWD.yaml): PLT test plan to program nRF91 via SWD
- `zephyr-nrf9160-at_client.hex` (Available from Nordic)

## PLT-200A connection

Use a USB 2.0 Type-A to micro-USB cable to connect the nRF91 DK *J4* micro-USB port to any of the
USB ports in the back of the PLT-200A.

## References

- [nRF9160 DK - nordicsemi.com](https://www.nordicsemi.com/Software-and-Tools/Development-Kits/nRF9160-DK)
