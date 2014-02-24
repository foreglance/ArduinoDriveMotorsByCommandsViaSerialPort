Drive motors with Arduino Motor shield by commands via serial port.

Awaiting text commands via serial port #1 - digital pins 0 (RX1), 1 (TX1).
Max command length - 64 chars.
Command ends with "new-line" char.
Diagnostics messages are sent back to serial port #1.

Commands control two motors drived by a Motor shield.

Following commands are supported (case-sensitive):
 "start" - start moving
 "stop" - stop moving
 "left" - turn left
 "right" - turn right
 "forward" - move forward
 "backward" - move backward

