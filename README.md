# Voron V2.4 Klipper Profile

_This is a work in progress; more so then usual since I have not completed the hardware build. Items not tested are commented out._

Software:
- [Klipper](https://github.com/KevinOConnor/klipper)
- [Moonraker](https://github.com/Arksine/moonraker)
- [Mainsail](https://github.com/meteyou/mainsail)

Hardware:
- Raspberry Pi 4B
- 2x BigTreeTech SKR 1.3 Controller Boards

Mods/Deviations (W.R.T. Stock V2.4):
- Raspberry Pi uses a [heatframe](https://smile.amazon.com/gp/product/B085XPHY77) for efficent passive cooling.
- Changed controller chamber fans to be controlled by each SKR (fans only operate when the drivers are active).
- 12V LED Strips (controlled by Z board) for chamber lighting.
- Edwardyeeks' [Braced Z Drive Motor/Tensioner](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/V2.4_z_drive_motor_tensioner_mod)
- Ellis' [Short Z Joints](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Short_Z_Joints)
- StvPtrsn's [Side Fan Supports w/o Tape](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/StvPtrsn/Side_Fan_Support_No_Tape)

Updates:
- All motors are functional. X/Y can home using the hall effect sensor.

- - - 
This repo based on f0or1s' [cr10_klipper repo](http://github.com/fl0r1s/cr10_klipper).
