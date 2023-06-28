# RLArduinoBoards
Repository for custom Arduino boards.

## Supported Boards
### RL1400
### RL2000
### IthProbe
  <li>Based on ItsyBitsy M0 Express</li>
  <li>Upgraded to a USBC connector for increased current capability.
  <li>VBus and VBat diodes, D5 level shifter, SPI flash and dotstar removed.</li>
  <li>2k I2C EEprom added at address 0x50 for storing calibration data.</li>
  </ul>
  <br>

## Arduino IDE Setup Instructions

<li>Copy and paste the following URL into the File > Preferences > "Additional Boards Manager" textbox.

```
https://raw.githubusercontent.com/reaylabs/RLArduinoBoards/master/CustomBoards/package_reaylabs_index.json
```
</li>
<li>
Go to Boards > "Add board definition" > Search for "Reay Labs" > Install RLArduinoBoards library
</li>
<li>
Go to Boards > "Add board definition" > Search for "SAMD" > Install Arduino SAMD Library
</li>