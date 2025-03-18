# Voron 2.4 300mm "darkteal" config files

This repository contains config files for my Voron 2.4 300mm "darkteal" printer, automatically
backed up by [Klipper-Backup 💾](https://github.com/Staubgeborener/klipper-backup).

The printer set up is stock, self-sourced, with the following changes and additions:
- Stealhburner with G2E extruder (LDO kit)
- Nitehawk-SB toolhead
- OMC 17HS19-2004S1 1.8° steppers
- BTT Manta M8P board with CM4 (8GB) and TMC2209 drivers
- Sensorless homing
- THE FILTER

On the software side:
- [TMC Autotune](https://github.com/andrewmcgr/klipper_tmc_autotune) with default 'auto' goal (silent Z and performance XY)
- Using [Klippain-Shaketune](https://github.com/Frix-x/klippain-shaketune) for resonance testing

I wrote all macros myself but took (sometimes heavy) inspiration from the following:
- [Klippain](https://github.com/Frix-x/klippain/)
- [Ellis' bed fans macros](https://github.com/VoronDesign/VoronUsers/blob/main/printer_mods/Ellis/Bed_Fans/Klipper_Macros)

