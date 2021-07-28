# Voron V2.823 Klipper Profile

Software:
- [Raspberry Pi OS Lite "Buster"](https://www.raspberrypi.org/software/operating-systems/#raspberry-pi-os-32-bit)
- [Klipper](https://github.com/KevinOConnor/klipper)
- [Moonraker](https://github.com/Arksine/moonraker)
- [Mainsail](https://github.com/meteyou/mainsail)

Hardware:
- Raspberry Pi 4B
- Fysetc Spider V1.0 Controller Board
- TMC2209 Stepper Drivers

Mods/Deviations (W.R.T. Stock V2.4):
- Raspberry Pi uses a [heatframe](https://smile.amazon.com/gp/product/B085XPHY77) for efficent passive cooling.
- 12V LED Strips for chamber lighting.
- Edwardyeeks' [Braced Z Drive Motor/Tensioner](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/V2.4_z_drive_motor_tensioner_mod)
- StvPtrsn's [Side Fan Supports w/o Tape](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/StvPtrsn/Side_Fan_Support_No_Tape)
- Changed controller chamber fans to be controlled (fans only operate when the drivers are active).
- Cork insulation directly under hotbed to protect electronic chamber from direct/radiated heat.
- Edwardyeeks' [Purge Bucket and Nozzle cleaner](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/Decontaminator_Purge_Bucket_&_Nozzle_Scrubber)
- BadNoob's [**A**fter**B**urner **B**ad**N**oob Version **30**](https://github.com/VoronDesign/VoronUsers/pull/302) (finally released/public)
- Wile-e1's [Deck Panel Support Clips](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/wile-e1/Deck_Panel_Support_Clips)
- Hartk's [AB Toolhead PCB](https://github.com/hartk1213/MISC/tree/main/PCBs/Afterburner_Toolhead_PCB)
- JosAr's [Klicky Probe](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/JosAr/Klicky-Probe)
- ProtoLoft/TitusLabs' [Z Calibration Plugin](https://github.com/protoloft/klipper_z_calibration)
- Hartk's [GE5C Z Bearings](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_GE5C)
- Hartk's [Pins Mode](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod)
- Hartk's [Y Endstop Relocation](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Y_Endstop_Relocation)
- Replaced the stock V2 X Carriage Frame w/ the stock V1.8 version (includes X endstop location).
- Phalanx' ["Other" Idlers](https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/Phalanx/Other-V2-Idlers)
- JaredC01's [Galileo Clockwork](https://github.com/JaredC01/Galileo)
- Leandromarceddu's [ADXL345 Galileo Mount](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/leandromarceddu/GalileoADXL)

Updates:
- Replaced all motions parts on the gantry w/ pinned parts. Relocated X/Y Endstops.
- Rewired entire machine w/ PTFE, added Hartk's Toolhead PCB, replaced Omron Probe w/ Klicky probe.
- Added code to allow moonraker's Update Manager to pull config changes.
- Replaced 2x SKR 1.3 controllers with single Fysetc Spider.
- System operational. Additional tuning and printing of remaining parts (skirts, exhaust, etc) in progress.
- Hotbed and hotend calibrated.
- First print (PLA) and machine serialized (V2.823).
- All motors are functional. X/Y can home using the hall effect sensor.

- - - 
This repo based on f0or1s' [cr10_klipper repo](http://github.com/fl0r1s/cr10_klipper), rpanfili's [woron-ht repo](http://github.com/rpanfili/voron-ht), and Zellneralex's [klipper_config repo](http://github.com/zellneralex/klipper_config) among many others.
It is a work in progress as I keept finding new and better ways to organize/tune my setup.
