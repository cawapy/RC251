# Radcomputer RC 25/1

Bike computer

## Characteristics

- Support BLE HR sensor
  - Auto connection
  - Show heart rate
  - Show heart beat indicator
  - Show battery status (if provided by sensor)
- Compatible with mount used by a German bike computer manufacturer
  - Show speed of bike
  - Wheel circumference adjustable via serial monitor (see below)
- Power supply through Micro-USB
  - Approx. 80 mA current draw (suitable for power banks)
- Dimensions approx. 72 mm x 36 mm x 16 mm
- Unique piece for private, non-commercial use

## Serial Monitor

- 115200 / 8 bits / no parity / 1 stop bit
- Commands
  - `c=####` = set wheel circumference to #### mm for bike speedometer
    - allowed values 100 - 3000
    - power-cycle to apply value
    - Example: `c=2230`
