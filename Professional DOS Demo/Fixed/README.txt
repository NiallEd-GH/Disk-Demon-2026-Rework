Mikrotronic-VTS Demo for Professional DOS
Fixed German and English versions


***   In order to run correctly, the following conditions must be observed for both emulated and real hardware environments:   ***

- THE DISK MUST NOT BE WRITE PROTECTED
- NO DEVICES OTHER THAN DRIVE 8 SHOULD BE ATTACHED
- In VICE, a stock drive type should be selected
- In Denise, either a 'stock' drive type or Professional DOS Expansion should be used

In an emulated environment, if not using a Professional DOS Expansion, I recommend using JiffyDOS as it will speed up some of the loading, especially when the program starts.
In a real environemt, the best option is to use a 1541 with a Professional DOS, Disk Demon or RapidDOS Professional board installed.
With any of the options, the program will 'stutter' when loading images unless Profesional DOS/Disk Demon/RapidDOS Professional is used

THE FIXED DEMO WILL NOW RUN CORRECTLY ON A 'STOCK' 1541 EITHER REAL HARDWARE OR EMULATION

THE DEMO WILL ALSO RUN ON A REAL 'STOCK' 1571

This demo was produced by Frank Schweigard in 1987 to introduce Professional DOS, provide installation instructions and highlight some of the benefits.
It appears to be a joint venture between Mikrotronic Michegan and VTS/MTS.

There are two Demos; one for the C64 & 1541 combination and the other for the C128 & 1571 combination

Most of the original demo is in German although the text on the images is in English.

In the English version, the files 'TFILE', 'TF2' & 'START THE DEMO' have been translated into English and reformatted.
The result is that the whole demo is now available in English and german

The general format of the Demo is 

Display some text, possibly with some special effects
Display an image
repeat

As the demo progresses, fewer images will be loaded.
The images are only loaded when needed and seem to be contained in the '.b' & '.v' files.
Possibly the file spr.dat is involved too

In VICE & DENISE, the demo will run if a drive is selected as Drive 8 and the drive type is set to NONE for drives 9, 10 & 11

The sound will 'stutter' and sometimes pause while an image is being loaded

In Denise, the demo will run normally if the Professional DOS expansion settings are used

Many thanks to FiDo on the Lemon64 Forum for fixing the bug with the stock 1541 and the tune selection options

NiallEd, 2 Nov 2026