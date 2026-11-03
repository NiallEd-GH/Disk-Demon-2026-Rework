Professional DOS VTS Demo (German version) - Fixed October 2026 by FiDo
FiDo Fix #2. It also incorporates Fix 1
Fix 1 : This fixes the problem with the Demo hanging when using the 1541 stock ROM or 1541 Jiffy DOS
Fix 2: It also corrects the bug in the music selection to reduce the number of tunes available to 2 rather than 4 (there are only 2)

Fix 1 changes the files:
 main.task1.prg
 main.task2.prg

Fix 2 changes the files
- demoloader -.prg
 -- loader --.prg

Note that the original name of  '-- loader --.prg' was '--> loader <--.prg' but NTFS/Windows/FAT does not allow the use of '<' or '>' in filenames