### Configuration Notes: {#Configuration Notes:}

---

### Configuration Mode Enable:

After power on, hold down the CONFIG button and press the RESET button at the same time, release the reset button first, and then release the CONFIG button after 2 seconds. The P9 RADIO can enter the configuration mode.

```
Configuration mode interface baud rate is fixed 9600
If a late configuration error occurs, it can be reconfigured through the configuration mode.
```

### Parameter Description:

The host settings are as follows:

1. Enter ATS101=0 Enter 0 - Host

2. Enter ATS102=2 Enter 2 - 57600 Serial Port Baud Rate

3. Enter ATS103=4 Enter 4 - 115200 Air Rate

4. Enter ATS105=1 Enter 1 - Host Device Address

5. Enter the ATS108=30 Enter 30-1000mw transmit power

6. Enter ATS133=1 Enter 1 - PTP Point to Point Mode

7. Enter ATS140=2 Enter 2 - Slave Target Address

8. Enter AT&W Enter to write settings to memory

The slave configuration is as follows:

1. Enter ATS101=2 Enter 2 - Slave

2. Enter ATS102=2 Enter 2 - 57600 Serial Port Baud Rate

3. Enter ATS103=4 Enter 4 - 115200 Air Rate

4. Enter ATS105=2 Enter 2 - Slave Device Address

5. Enter the ATS108=30 Enter 30-1000mw transmit power

6. Enter ATS133=1 Enter 1 - PTP Point to Point Mode

7. Enter ATS140=1 Enter 1 - Host Target Address

8. Enter AT&W Enter to write settings to memory

### Setting Options Query Table {#Setting Options Query Table}

ATS101 type

0-host, 1-relay, 2-slave

ATS102 serial port baud rate

0-230400, 1-115200, 2-57600, 3-38400, 4-28800, 5-19200, 6-14400, 7-9600,

8-7200, 9-4800, 10-3600, 11-2400, 12-1200, 13-600, 14-300

ATS103 air speed

0-172800, 1-230400, 2-276480, 3-57600, 4-115200

ATS105 device address

2~65534

ATS108 transmit power

20-100, 21-125, 22-160, 23-200, 24-250, 25-320, 26-400, 27-500, 28-630, 29-800, 30-1000mw

ATS133 communication mode

0-Point-to-Multipoint, 1-point-to-point, 2-Mesh, 3-Mesh with Roaming

ATS140 destination address

PMP - Master S140=65535, Remote S140=1

PP - Master S140=UA of Remote, Remote S140=1 \(Master\)