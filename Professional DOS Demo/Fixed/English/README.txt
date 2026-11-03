Professional-DOS-VTS-Release-Demo_Eng_Fix.d64
This is the fixed version of the English Translation of the VTS Demo, October 2026
It incorporates FiDo Fix1, FiDo Fix2 & the 'START THE DEMO' fix

FiDo Fix 1
Fixes the problem with the Demo hanging when loading images using the Stock 1541 or JiffyDOS 1541 ROMs

FiDo Fix 2
Fixes the bug where it was possible to choose 4 music options but only 2 are available. Choosing 3 or 4 would crash the program
This fix reduces the music options to 1 or 2

'START THE DEMO' fix
If an option other than '1' or '2' is chosen then the program halts
This fix checks for and ignores any responses other than '1' or '2'