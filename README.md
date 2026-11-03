<img width="1024" height="768" alt="Collection-C" src="https://github.com/user-attachments/assets/3f3ac5c0-6cb4-4e48-a47d-310837d9d5db" />

# Disk-Demon-2026-Rework
A rework of the original 1987 Disk Demon using components available in 2026. 

A couple of years ago I rediscovered my old Commodore 64 setup from the 1980s.

While I was getting it all working again, I noticed that one of the disk drives contained a board with words 'Disk Demon' written on one of the ICs. I was curious to find out more about it.....

It turns out that Disk Demon was a version of Professional DOS. At the time, Disk Demon/Professional DOS claimed to be the fasted floppy disk accelerator for the Commodore 64 in the world !

It was released and sold in the UK by Datel Electronics for the Commodore 1541 disk drive. Unlike Professional DOS, which was available for both the Expansion Port and User Port, Disk Demon was only available for the User Port.

As few people seem to have heard of it, I decided to make this lesser known variant of Professional DOS available again in 2026.

It was important that all the parts should be easy to source and the biggest stumbling block was that the original board used an 82S123, 32x8 Bipolar PROM but blank 82S123 PROMs are difficult to find and also, much harder to program than EPROMs.

As EPROMs are not fast enough to replace the PROM, I looked at a PLD.

Although the Lattice GAL is the one most people have heard of, they are no longer made.

Fortunately, a company called Microchip are still making their version of the 16V8 and 22V10 GALs known as the ATF16V8 and ATF22V10.

I redrew the schematic in Kicad, modified the original design to use an ATF16V8 (& added a few bypass capacitors while I was at it) and created a new PCB.

The board is similar in appearance to the original but it is not identical so I decided to call it 'Disk Demon 2026 Rework'

The board has been tested in several different 1541 disk drives, both ALPS & Newtronics and performs well.

Datel originally claimed that a 202 Block file could be loaded in around 2.5 seconds. I have not been able to reproduce that time with either the original board or this rework. But, I have managed to load 202 blocks in 3.5 seconds which is good enough for me.

I have included a Kicad Schematic for both the original 1987 Disk Demon and the 2026 Rework.

There are also Gerber files for the 'Rework' PCB, along with all the programming information for the ATF16V8, the 256kb Disk Demon EPROM and the C64 Disk Demon Kernal ROM.

For those planning to make their own Disk Demon, there is a step by step assembly guide.

The User Port version of the Professional DOS Kernal ROM for the Commodore 64 is included in case you want to compare it to the Disk Demon C64 Kernal ROM

Datel also sold a 'Disk Demon Utility Disk' so there is a D64 image for that.

I have reproduced the Disk Demon documentation which I suggest reading if you want to get the most from the board.

The most common problem getting the board to work is down to poor connections where the board plugs into the 6502 socket on the 1541 system board. I strongly suggest that you replace the original 40 pin CPU socket on the 1541 system board with a new one.

The same goes for the 6522 VIA socket !

If you have any issues, please raise them in this thread on Lemon64

https://www.lemon64.com/forum/viewtopic.php?p=1106892

Good luck and enjoy super fast Commodore 64 loading and saving

NiallEd (October 2026)
