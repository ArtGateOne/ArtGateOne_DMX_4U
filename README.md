# ArtGateOne_DMX_4U
This is only test sketch for Arduino Mega - 4 universe dmx out - can dont work


This is simple artnet node.

Required: Arduino MEGA

Ethernet Shield with W5100/W5500

OLED display 128x32 I2C

4 x module with max485

Universal Ethernet to DMX Interface

4 DMX512 Port

Art-Net streaming DMX support

Can be used with any Art-Net compliant console or DMX software

Universe selectable by web browser

Stand-alone DMX buffer mode


---------------
WIRING

OLED DISPLAY I2C

VCC --> 5v or 3.3v

GND --> GND

SCL --> SCL

SDA --> SDA


------------------
MAX485 modules

RO --> not connnected

RE + DE + VCC --> 5v

DI --> TX (D1 PIN)

GND --> GND

A --> DMX OUT

B --> DMX OUT



--------------------
max modules DI pins to TX0, TX1, TX2 & TX3

