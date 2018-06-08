# Use hardware connection

---

#### Factory paired: {#factory paired:}

The factory default is airspeed 115K, interface rate is 57600, peer-to-peer broadcast mode

To modify the configuration, see the Software Configuration Guide.

#### Connection with Flight Control: {# Connection with Flight Control:}

PixHack: Radio Interface Plugged into Flight Control

Pixhawk: plug into the flight controller's telem1 or telem2 interface

#### Ground station use: {# ground station use:}

In theory, the ground stations of the PIX are compatible. Please select 57600 baud rate when connecting. Note whether the driver is installed correctly and whether the port number is selected.

## Power Requirements:

The ground end must ensure that the usb port supply current is greater than 1A, and it needs independent power supply. If the aircraft end is less than 1A in flight control output, it needs independent power supply.

### Apply to other systems:

If only the wireless data transmission module is used, please follow the interface definition and the system connection (RX-TX TX-RX GND-GND)

The default standard interface rate is 57600. The required interface baud rate can be changed according to the requirements.
