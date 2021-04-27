# Test plans for nRF9160 DK

Example project targeting Nordic's **nRF9160 DK** development kit.

- [at\_client-JLink.yaml](at_client-JLink.yaml): PLT test plan to program nRF91 DK via USB (JLink)
- [at\_client-SWD.yaml](at_client-SWD.yaml): PLT test plan to program nRF91 via SWD
- `zephyr-nrf9160-at_client.hex` (Available from Nordic)

## PLT-200A connection

To connect the nRF9160 Cortex-M33 through the on-board JLink programmer of the nRF9160 DK,
use a USB 2.0 Type-A to micro-USB cable to connect the nRF91 DK *J4* micro-USB port to any of the
USB ports in the back of the PLT-200A and use the [at\_client-JLink.yaml](at_client-JLink.yaml)
test plan.

To program the nRF9160 Cortex-M33 over SWD, use the [at\_client-SWD.yaml](at_client-SWD.yaml)
test plan, and connect the PLT-200A SWD signals to the nRF9160 DK *P3* Debug socket as below:

| PLT-200A SWD pin | PLT-200A  Signal | nRF9160 Function | P3 Pin   |
|:----------------:|------------------|------------------|:--------:|
| 1                | SWD\_VDD         | VDD              |  1       |
| 2                | SWD\_SWDIO       | SWDIO            |  2       |
| 3                | SWD\_NRST        | RESET            | 10       |
| 4                | SWD\_SWCLK       | SWDCLK           |  4       |
| 5                | GND              | GND              |  3, 5, 9 |
| 6                | SWD\_SWO         | SWO              |  6       |

## References

- [nRF9160 DK - nordicsemi.com](https://www.nordicsemi.com/Software-and-Tools/Development-Kits/nRF9160-DK)
