Mikrotronic-VTS Demo for Professional DOS
Original German and English versions

THESE VERSIONs OF THE DEMO CURRENTLY WILL NOT RUN CORRECTLY ON A 'STOCK' 1541 EITHER REAL HARDWARE OR EMULATION

Fortunately, FiDo from the Lemon64 Forum has fixed this issue. The fixed versions can be found in the 'Fixed' folder.

I have left these originals here in case anyone wants to compare them to the fixed version.

The following README applies to the original versions

***   In order to run correctly, the following conditions must be observed for both emulated and real hardware environments:   ***

- THE DISK MUST NOT BE WRITE PROTECTED
- NO DEVICES OTHER THAN DRIVE 8 SHOULD BE ATTACHED
- In VICE, a 1571 drive type should be selected
- In Denise, either a 1571 drive type or Professional DOS Expansion should be used

In an emulated environment, if not using a Professional DOS Expansion, I recommend using 1571 & JiffyDOS as it will speed up some of the loading, especially when the program starts.
In a real environemt, the best option is to use a 1541 with a Professional DOS, Disk Demon or RapiDOS Professional board installed.
With any of the options, the program will 'stutter' when loading images unless Profesional DOS/Disk Demon/RapiDOS Professional is used

THE DEMO WILL RUN ON A REAL 'STOCK' 1571

This demo was produced by Frank Schweigard in 1987 to introduce Professional DOS, provide installation instructions and highlight some of the benefits.
It appears to be a joint venture between Mikrotronic Michegan and VTS/MTS.

There are two Demos; one for the C64 & 1541 combination and the other for the C128 & 1571 combination

Most of the original demo is in German although the text on the images is in English.

In the English version, the files 'TFILE', 'TF2' & 'START THE DEMO' have been translated into English and reformatted.
The result is that the whole demo is now available in English and german

Although there are various launcher programs, the Demo really starts with the launch of either "main.task1" prg or  "main.task2" prg 
This reads all the text for the demo from "tfile" seq
As far as I can tell, "main.task2" prg does the same thing but it has a different sound track

The general format of the Demo is 

Display some text, possibly with some special effects
Display an image
repeat

As the demo progresses, fewer images will be loaded.
The images are only loaded when needed and seem to be contained in the '.b' & '.v' files.
Possibly the file spr.dat is involved too

Oddly, on a 1541, the demo seems to require a Professional DOS/Disk Demon board installed in the 1541 drive in order to work correctly.
Without the board, the demo can still be loaded (slowly) and will start to run as expected. But, at the end of the first screen of text,
it tries to load an image and, after some disk activity, the C64 will hang.

If a Professional DOS board is installed but the parallel cable is removed then the demo will load and run albeit much more slowly and erratically.

Also, if the Professional DOS board is removed and either a SpeedDOS or RapiDOS (not professional) ROM is installed in
place of the standard CBM DOS ROM (901229-05), then the demo will run normally (again with much slower disk access)

In VICE, the demo will run if a 1571 drive is selected as Drive 8 and the drive type is set to NONE for drives 9, 10 & 11
The sound will 'stutter' and sometimes pause while an image is being loaded

In Denise, the demo will run slowly if a 1571 drive (with stock ROM) is used instead of a 1541.
Again, the sound will 'stutter' and sometimes pause while an image is being loaded

In Denise, the demo will run normally if the Professional DOS expansion settings are used

NiallEd, 2 Nov 2026