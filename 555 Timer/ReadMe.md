Functions of the eight pins on a 555 timer IC:

| Pin | Label | Function | Description |
| :---: | :--- | :--- | :--- |
| 1 | GND | Ground connection | Connects the chip to the negative power rail (0V) |
| 2 | TRIG | Starts output | When capacitor voltage falls below $\frac{1}{3} V_{CC}$, Pin 3 Turns HIGH |
| 3 | OUT | IC output | Delivers the pulsing square wave or steady high/low power to load |
| 4 | RST | Timer reset | Overrides all timing inputs; connected to ground then resets the timer (force Pin 3 to LOW); connected to $V_{CC}$ then does not resets |
| 5 | CONT | Threshold override | Allows external voltages to alter the internal reference levels (TRIG and THRES); if unused then left unconnected or bypassed with a 10nF capacitor |
| 6 | THRES | Ends output | When capacitor voltage goes above $\frac{2}{3} V_{CC}$, Pin 3 Turns LOW |
| 7 | DISCH | Capacitor discharge | Opens an internal path to Ground when Pin 3 goes LOW to discharge the capacitor |
| 8 | VCC | Power supply | Connects the chip to positive voltage (from +4.5V to +15V) |
