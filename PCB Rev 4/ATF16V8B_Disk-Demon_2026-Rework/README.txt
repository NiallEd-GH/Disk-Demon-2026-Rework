Programming info for the ATF16V8B used in the Disk Demon 2026 Rework
Last update 13 Aug 2026

The Disk Demon 2026 Rework uses a Microchip (formerly Atmel) ATF16V8 PLD
This must be programmed correctly in order to work in the Disk Demon 2026 Rework PCB

It can be programmed using a XGeku T48 Programmer using the ATF16V8B option

The file to use for programming is DD-ATF16V8B.jed

I suggest disabling both the encryption and lock bit options prior to programming.
It has not been tested with either of these options enabled

This project was developed using WinCUPL II available from Microchip
https://www.microchip.com/en-us/development-tool/wincupl
All the related WinCUPL files are here but, due to the vagaries of WinCUPL II,
the DD-ATF16V8B.wcp Project file needs to be launched from the following directory

C:\WinCUPL\Disk-Demon-ATF16V8B\

If you want to change this location, open DD-ATF16V8B.wcp with a text editor and 
change the paths for the following lines
WCP_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.wcp
PLD_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.pld
ABS_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.abs
JED_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.jed
LST_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.lst
SI_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.si
SIM_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.sim
SO_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.so
WO_Name=C:\WinCUPL\Disk-Demon-ATF16V8B\DD-ATF16V8B.wo
