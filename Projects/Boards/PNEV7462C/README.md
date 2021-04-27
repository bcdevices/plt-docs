# Test Plans for NXP PNEV7462C

Example firmware and test plan targeting NXP's *PNEV7462C evalation board*.

- `suite-program-PN7462AU_ex_phExMain.yaml` : PLT test plan for `PN7462AU_ex_phExMain.axf`
- `PN7462AU_ex_phExMain.axf` : Example firmware for PNEV7462C

## PLT-200A connection

To program the NXP PN7462AU over SWD, connect the PLT-200A SWD signals
to the JP4 LPC-Link connector over the PNEV7462C board as follows:

| PLT-200A SWD Pin |PLT-200A Signal |JP4 Pin | Net      |
|:----------------:|:--------------:|:------:|:--------:|
| 1                |``SWD_VDD``     |1       |``3V3``   |
| 2                |``SWD_SWDIO``   |2       |``SWDIO`` |
| 3                |``SWD_NRST``    |10      |``RST_N`` |
| 4                |``SWD_SWCLK``   |4       |``SWDCLK``|
| 5                |``GND``         |3       |``GND``   |
| 6                |``SWD_SWO``     |-       |n.c.      |

- [PNEV7462C Product Information | NXP](https://www.nxp.com/part/PNEV7462C#/)
