# Firmware
PG LAB Electronics E-BOARD Firmware.


## Release History

1.0.3 [22-12-2024] 
- Fix Bug on sending I2C to E-RELAY. Avoid top send any command to not connected E-RELAY devices.
- Update e-mail and web site contact
- Fix the default E-BOARD name with upper case

1.0.2 [01-10-2024] 
- Release Build !!!!
- Added Serial Number
- Fix comment on html pages for E-Board internal web server
- Improve LWIP dynamic memory allocator
- Refactoring of how to use Daylight Saving Time

1.0.1  [Not Released]
- Fix MAC ADDRESS format to be in the right format ... this avoid mac as FC:F:E7:D8:24:E7 but change in correct FC:0F:E7:D8:24:E7
- When receiving a mqtt status change, always return the new state also if not changed. This help HA to be in sync with E-Board status
  It seems a problem of the new HA April 2024 build
- Added a stack overflow check and reboot in case.
- Reduce RAM memory footprint, removed unused html page.

1.0.0  [Not Released]
- Initial build

