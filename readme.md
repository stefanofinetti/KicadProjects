# Kicad Projects File

This is a repository of my Kicad projects. Not everyone is working, I will list here the ones that I used and that I already sent to JLCPCB for printing.

* FCU_Mainboard_V3: a complete mainboard for FCU and both EFIS panels for Fenix A319/320/321. It is based on ATMega2560 chip with CH340G USB-To-Serial converter. All the components are SMD except for pin headers and the power selector switch to change between USB power and Bootloading using another card as Programmer. It works with Elral/Gagaru custom device firmare for Mobiflight since it has 6 SSD1306 OLED displays
* RMP_V2: a Radio Management Panel using ATMega2560 using two small OLED (0.96"), basically half the height of an SSD1306 OLED. It has a 9548APW chip and a separate 5V line for backlighting. It is meant to be mounted directly behind a 3d printed panel and provides backlighting to buttons and writings.
* LTS_Spooler: not Mobiflight related, it's the circuit board usable inside the fantastic LTS_Spooler project you can find here: https://makerworld.com/en/models/448008#profileId-354782
