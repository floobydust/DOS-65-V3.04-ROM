# DOS-65-V3.04-ROM
Updated Version for DOS/65 to Version 3.04 ROM

Some additional updates to streamline the CCM, PEM and SIM modules. Code is a bit shorter and some quicker routines provide some minor performance updates.

This version supports a prototype 3.3V system based on the C02 Pocket SBC V2, using a SC28L92 DUART and a Hitachi Microdrive

Updated BIOS supports the new hardware and the new SIM module supports the second UART port as Reader/Punch

Note that this version also uses CMOS opcodes and addressing modes! Requires an updated BIOS/Monitor now at version 4.01

The code has been broken into multiple code modules for a Base, CCM, PEM and SIM source files. WDC Tools is required to assemble and link. Only the core code is included in the ZIP file. Other utilities such as Super Directory, Submit, etc. can be brought over from the 3.03 ROM version.
