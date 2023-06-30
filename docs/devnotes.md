# Celeste / Ice Climber NES ROM hack notes

Title screen location:

0x50f3 == ICE
0x5127 == CLIMBER

top of C / E : 60 61 61

MOUNTAIN  @ 0x51BB

NINTENDO @ 0x51F3


1 PLAYER
2 PLAYER

0x526C / 0x52CA

MADELINE
BADELINE

3C 33 35 3D 37 3B 5A 3D
34 33 35 3D 37 3B 5A 3D


Badeline / Bird palette:
0x06BC -- bird character palette
0x3607 -- same palette
0x5306 -- bird bonus tally icon


Bonus level cloud code:
@E614 in RAM, 0x2624 in .nes:
STA #$00

A9 00 -> A9 02  to change cloud palette from 0 to 2
