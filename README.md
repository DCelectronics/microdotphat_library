# microdotphat_library

## Simple Micro Dot pHAT Arduino library with clock sample for M5Stack BASIC

##### Simple Micro Dot pHAT Arduino library<br/>Copyright (C) 2020 Martin Lukasek <martin@lukasek.cz>
###### This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
###### This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
###### You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>. 
###### Clock sample is created for M5Stack, connect the followsin 4 wires:
    Connect 5V (pin 2 or 4) of Micro Dot pHAT to 5V pin of M5Stack
    Connect GND (pin 6) of Micro Dot pHAT to GND pin of M5Stack
    Connect SDA (pin 3) of Micro Dot pHAT to SDA pin of M5Stack (GPIO 21)
    Connect SCL (pin 5) of Micro Dot pHAT to SCL pin of M5Stack (GPIO 22)
    
###### This software is based on work of  clarktans:
    https://github.com/clarktans/microdot-clock
    TimeNTP_ESP8266WiFi.ino
    Example showing time sync to NTP time source

### To Do
Modify the library to support four IS31FL3730 matrix driver chips (I2C addresses 0x60, 0x61, 0x62, and 0x63) on a custom board for total 8 digits. 
