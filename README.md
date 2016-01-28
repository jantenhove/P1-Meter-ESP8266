# P1-Meter-ESP2866
Software for the ESP2866 that sends P1 smart meter data to Domoticz (with CRC checking and OTA firmware updates)

### Installation instrucions
- Make sure that your ESP2866 can be flashed from the Arduino environnment: https://github.com/esp8266/Arduino
- Install the SoftSerial library from: https://github.com/plerup/espsoftwareserial
- Place all files from this repository in a directory. Open the .ino file.
- Adjust WIFI, Domoticz and debug settings at the top of the file
- Compile and flash
