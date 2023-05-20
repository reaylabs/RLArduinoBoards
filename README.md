# RLArduinoBoards
Repository for custom Arduino boards.

## Supported Boards
### RL1400
### RL2000
  <li>Based on ItsyBitsy M0</li>
  <li>Upgraded to a USBC connector for increased current capability.
  <li>VBus and VBat diodes, D5 level shifter, SPI flash and dotstar removed.</li>
  <li>2k I2C EEprom added at address 0x50 for storing calibration data.</li>
  <li>Changed the pinout to sequential order. Also added the CC1 and CC2 USBC pins</li>
  </ul>

## Arduino IDE

Copy and paste the following URL into the File > Preferences > "Additional Boards Manager" textbox.

```
https://raw.githubusercontent.com/reaylabs/RLArduinoBoards/master/CustomBoards/package_reaylabs_index.json
```

The latest version is 1.1.0

Make sure to also install the Arduino SAMD Library at the same time.

Boards > "Add board definition" > Search for "Reay Labs" > Install RLArduinoBoards library

Boards > "Add board definition" > Search for "SAMD" > Install Arduino SAMD Library