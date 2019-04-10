Probe and Fixture connectors
----------------------------

DUT UART/Analog Probe connector
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- TC2030-IDC, 6-pin Tag-Connect (UART)
- PLT200A: J9 (CnC Tech 3020-06-0200-00)

=======  ==============  =======  =========================
Pin      UART Signal     Alt      Description
=======  ==============  =======  =========================
1        UART0_RXD       DATP08   UART Receive
2        UART0_TXD       DATP09   UART Transmit
3        UART0_CTS#      DDTP15   UART Clear To Send
4        UART0_RTS#      DDTP16   UART Ready To Send
5        UART0_VDD       -        DUT Power
6        GND             -        Ground
=======  ==============  =======  =========================

DUT SWD Probe connector
^^^^^^^^^^^^^^^^^^^^^^^

- TC2030-IDC, 6-pin Tag-Connect (SWD)
- PLT200A: J8 (CnC Tech 3020-06-0200-00)

=======  ===========  ====================
Pin      SWD Signal   Description
=======  ===========  ====================
1        SWD_VDD      DUT Power
2        SWD_SWDIO    Serial Wire Data I/O
3        SWD_NRST     System Reset
4        SWD_SWCLK    Serial Wire Clock
5        GND          Ground
6        SWD_SWO      Serial Wire Output
=======  ===========  ====================


DUT JTAG Probe connector
^^^^^^^^^^^^^^^^^^^^^^^^

- TC2050-IDC, 10-pin Tag-Connect
- PLT-200A: J11 (CnC Tech 3020-10-0200-00)

=======  ===================  ==================
Pin      Cortex Debug Signal  Description
=======  ===================  ==================
1        +3V3                 Debug Rail Voltage
2        JTAG_TMS             Test Mode Select
3        GND                  Ground
4        JTAG_TCK             Test Clock Pin
5        JTAG_VCC             DUT Power
6        JTAG_TDO             Test Data Out
7        n.c.                 -
8        JTAG_TDI             Test Data In
9        n.c.                 -
10       JTAG_TRST            System Reset
=======  ===================  ==================

DUT Power Fixture Connection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Connector: Molex Micro-FIT; 430450400

.. figure:: images/pwr4-socket-drawing.svg

   Face view of Molex 430450400 Micro-FIT header on PLT rear

=======  ===========  ============================
Pin      Signal       Description
=======  ===========  ============================
1        GND          GND
2        5VOUT        5V
3        3V3OUT       3.3V
4        VARVOUT      Variable DC (2V - 12V)
=======  ===========  ============================

DUT ICT Fixture Connection
^^^^^^^^^^^^^^^^^^^^^^^^^^

Connector: Harting Elektronik 09565527613 78 Pin D-Sub

.. figure:: images/hd78-drawing.svg

   Face view of Female HD78 receptacle (J2) on PLT rear


=======  ===========  ============================
Pin      Signal       Description
=======  ===========  ============================
1        PPC_CLK01    Dedicated Clock Signal
2        GND          GND
3        PPC_CLK02    Dedicated Clock Signal
4        GND          GND
5        PPC_ADG0_A0  Analog MUX #0: A0
6        PPC_ADG0_A1  Analog MUX #0: A1
7        PPC_ADG0_A2  Analog MUX #0: A2
8        PPC_ADG0_A3  Analog MUX #0: A3
9        PPC_ADG0_EN  Analog MUX #0: Enable
10       GND          GND
11       PPC_ADG0     Analog MUX #0: Analog
12       PPC_ADG1_A0  Analog MUX #1: A0
13       PPC_ADG1_A1  Analog MUX #1: A1
14       PPC_ADG1_A2  Analog MUX #1: A2
15       PPC_ADG1_A3  Analog MUX #1: A3
16       PPC_ADG1_EN  Analog MUX #1: Enable
17       PPC_ADG1     Analog MUX #1: Analog
18       GND          GND
19       PPC_A0       DATP00; Dedicated Analog
20       PPC_A1       DATP01; Dedicated Analog
21       PPC_A2       DATP02; Dedicated Analog
22       PPC_A3       DATP03; Dedicated Analog
23       PPC_A4       DATP04; Dedicated Analog
24       PPC_A5       DATP05; Dedicated Analog
25       PPC_A6       DATP06; Dedicated Analog
26       PPC_A7       DATP07; Dedicated Analog
27       GND          GND
28       PPC_A8       DATP08; Dedicated Analog
29       PPC_A9       DATP09; Dedicated Analog
30       PPC_A10      DATP10; Dedicated Analog
31       PPC_A11      DATP11; Dedicated Analog
32       PPC_A12      DATP12; Dedicated Analog
33       PPC_D12      DDTP12; Digital
34       PPC_D13      DDTP13; Digital
35       PPC_D14      DDTP14; Digital
36       GND          GND
37       +3V3         PPC Power supply
38       +12V         PPC Power supply
39       +5V          PPC Power supply
40       PPC_D0       DDTP00; Digital
41       PPC_D1       DDTP01; Digital
42       PPC_D2       DDTP02; Digital
43       PPC_D3       DDTP03; Digital
44       PPC_D4       DDTP04; Digital
45       PPC_D5       DDTP05; Digital
46       PPC_D6       DDTP06; Digital
47       PPC_D7       DDTP07; Digital
48       PPC_D8       DDTP08; Digital
49       PPC_D9       DDTP09; Digital
50       PPC_D10      DDTP10; Digital
51       PPC_D11      DDTP11; Digital
52       GND          GND
53       GND          GND
54       SWD_VDD      SWD: VDD
55       SWD_NRST     SWD: NRST
56       SWD_SWDIO    SWD: SWDIO
57       SWD_SWCLK    SWD: SWCLK
58       SWD_SWO      SWD: SWO
59       JTAG_VCC     JTAG: VCC Debug Rail Voltage
60       CAN_H        CAN: H
61       CAN_L        CAN: L
62       JTAG_TMS     JTAG: TMS Test Mode Select
63       JTAG_TCK     JTAG: TCK Test Clock Pin
64       JTAG_TDO     JTAG: TDO Test Data Out
65       JTAG_TDI     JTAG: TDI Test Data In
66       JTAG_TRST    JTAG: RESET System Reset
67       UART1_VDD    UART1: VDD
68       UART1_CTS#   UART1: Clear To Send
69       UART1_RTS#   UART1: Ready To Send
70       UART1_RXD    UART1: Receive
71       UART1_TXD    UART1: Transmit
72       UART0_VDD    UART0: VDD
73       UART0_CTS#   UART0: Clear To Send (Alt: DDTP15)
74       UART0_RTS#   UART0: Ready To Send (Alt: DDTP16)
75       UART0_RXD    UART0: Receive (Alt: DATP08)
76       UART0_TXD    UART0: Transmit (Alt: DATP09)
77       PPC_SDA      I2C: Data
78       PPC_SCL      I2C: Clock
=======  ===========  ============================


Compatible Cable Assemblies:

- Harting Elektronik CS-DSDHD78MM0-002.5 CABLE ASSY HD78 SHLD GRAY 762MM
