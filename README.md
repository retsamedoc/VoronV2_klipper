# Voron V2.823 Klipper Profile

Software:
- [Raspberry Pi OS Lite "Buster"](https://www.raspberrypi.org/software/operating-systems/#raspberry-pi-os-32-bit)
- [Klipper](https://github.com/KevinOConnor/klipper)
- [Moonraker](https://github.com/Arksine/moonraker)
- [Mainsail](https://github.com/meteyou/mainsail)

Hardware:
- Raspberry Pi 4B
- 2x BigTreeTech SKR 1.3 Controller Boards

Mods/Deviations (W.R.T. Stock V2.4):
- Raspberry Pi uses a [heatframe](https://smile.amazon.com/gp/product/B085XPHY77) for efficent passive cooling.
- 12V LED Strips (controlled by Z board) for chamber lighting.
- Edwardyeeks' [Braced Z Drive Motor/Tensioner](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/V2.4_z_drive_motor_tensioner_mod)
- Ellis' [Short Z Joints](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Short_Z_Joints)
- StvPtrsn's [Side Fan Supports w/o Tape](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/StvPtrsn/Side_Fan_Support_No_Tape)
- Changed controller chamber fans to be controlled by each SKR (fans only operate when the drivers are active).
- Cork insulation directly under hotbed to protect electronic chamber from direct/radiated heat.
- Edwardyeeks' [Purge Bucket and Nozzle cleaner](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/Decontaminator_Purge_Bucket_&_Nozzle_Scrubber)

Updates:
- System operational. Additional tuning and printing of remaining parts (skirts, exhaust, etc) in progress.
- Hotbed and hotend calibrated.
- First print (PLA) and machine serialized (V2.823).
- All motors are functional. X/Y can home using the hall effect sensor.

- - - 
This repo based on f0or1s' [cr10_klipper repo](http://github.com/fl0r1s/cr10_klipper), rpanfili's [woron-ht repo](http://github.com/rpanfili/voron-ht), and Zellneralex's [klipper_config repo](http://github.com/zellneralex/klipper_config) among many others.
It is a work in progress as I keept finding new and better ways to organize/tune my setup.
