# Example Test Plan for Programming the TI CC1352 Launchpad

## Requirements

* [TI CC1352 Launchpad](https://www.ti.com/tool/LAUNCHXL-CC1352R1)
* [PLT-300A](https://bcdevices.com/pages/plt-300a)
* [NXP MCU-Link CMSIS-DAP Interface](https://www.nxp.com/design/design-center/software/development-software/mcuxpresso-software-and-tools-/mcu-link-debug-probe:MCU-LINK)

## Setup

1. Connect the MCU-Link to the PLT-300A using USB.
2. Connect the MCU-Link to the TI CC1352 Launchpad using the 10-pin Cortex Debug ribbon cable.
	* The ribbon cable should be connected to the "Target In" port on the TI CC1352 Launchpad.
3. Power the TI CC1352 Launchpad externally. Don't connect the TI CC1352 Launchpad to the PLT-300A
   using USB, the programming interface on the TI CC1352 Launchpad is not supported by the PLT-300A,
   and will interfere with programming.