# LY10 DEMO Board

Example BLE firmware and PLT test plans for the LY10-DEMO board.

- `ICTDemoTestPlanV1.2.yaml`: ICT test plan programming `ly10-demo-fw-0.1.8.hex`
- `ICTDemoTestPlanV1.3.yaml`: ICT test plan programming `ly10-demo-fw-0.1.8.hex`
- `ICTZephyrTestPlanV1.3.yaml`: ICT test plan programming `ly10-zephyr-fw-0.1.2.hex`
- `ly10-demo-fw-0.1.0.hex`: Firmware v0.1.0
- `ly10-demo-fw-0.1.4.hex`: Firmware v0.1.4; White LED animation
- `ly10-demo-fw-0.1.7.hex`: Firmware v0.1.7; Yellow LED animation
- `ly10-demo-fw-0.1.8.hex`: Firmware v0.1.8; Green LED animation
- `ly10-zephyr-fw-0.1.2.hex`: Zephyr-based firmware v0.1.2
- `suite-LY10-DEMO-0.1.0.yaml`: PLT test plan programming `ly10-demo-fw-0.1.0.hex`
- `suite-LY10-DEMO-0.1.4.yaml`: PLT test plan programming `ly10-demo-fw-0.1.4.hex`
- `suite-LY10-DEMO-0.1.7.yaml`: PLT test plan programming `ly10-demo-fw-0.1.7.hex`
- `suite-LY10-DEMO-0.1.8.yaml`: PLT test plan programming `ly10-demo-fw-0.1.8.hex`
- `suite-LY10-ZEPHYR-0.1.2.yaml`: PLT test plan programming `ly10-zephyr-fw-0.1.2.hex`

Not included (available from Nordic):

- `s132_nrf52_6.0.0_softdevice.hex`: BLE stack, required for ly10-demo-fw (but not for ly10-zephyr-fw)

## PLT-200A connection

For the `suite-LY10-....yaml` test plans, use a Tag-Connect TC-2030-IDC programming cable plugged
into the SWD port on the rear of the PLT-200A.

The `ICT....yaml` test plans are meant for use with the PLT ICT fixture equipped with
a LY10-DEMO Pogo-Pin Cassette (PPC).
