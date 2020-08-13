# Test Plans for Microchip Explorer 8

Example firmware and test plan targeting Microchip's *Explorer 8* evaluation
board.

- `PIC18F25K20_Exp8_v345_X.X.production.hex`: Explorer8 demo firmware for PIC18F25K20
- `PIC18F25K20_Exp8_v345_X.X.production.yaml`: Test plan to program `PIC18F25K20_Exp8_v345_X.X.production.hex`

## PLT-200A connection (JTAG)

| PLT-200A      | JTAG pin    | PIC18 |
|---------------|:-----------:|-------|
| +3V3          | 1           | n.c.  |
| JTAG\_TMS     | 2           | PGD   |
| GND           | 3           | GND   |
| JTAG\_TCK     | 4           | VPP   |
| JTAG\_VCC     | 5           | VDD   |
| JTAG\_TDO     | 6           | n.c.  |
| n.c.          | 7           | n.c.  |
| JTAG\_TDI     | 8           | PGC   |
| n.c.          | 9           | n.c.  |
| JTAG\_TRST    | 10          | n.c.  |
