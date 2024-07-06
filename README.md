# Celeste / Ice Climber NES ROM Hack

A [Celeste](https://www.celestegame.com/) themed ROM hack for the NES game [Ice Climber](https://www.romhacking.net/games/844/) (1984).

<img alt="ROM hack title screen" src="/img/titlescreen.png" width=50%>

Mainly sprite and palette modifications.

<img alt="ROM hack bonus stage" src="/img/bonusstage.png" width=50%>
<img alt="ROM hack 2 player mode" src="/img/2player.png" width=50%>
<img alt="ROM hack summary screen" src="/img/summary.png" width=50%>

## Features
* Celeste title screen (in the Ice Climber font)
* 1 Player / 2 Player →  Madeline / Badeline
* Lives indicator →  Crystal hearts
* Bird (Nitpicker) colour change (red →  blue)
* Ice hammer cursor →  Crystal heart on main menu
* Madeline sprites and palette
* Badeline palette, separate bird and P2 palettes
* Bonus level clouds changed to palette 2 (orange/white)

## ROM Information
```
Database match: Ice Climber (USA, Europe, Korea)
Database: No-Intro: Nintendo Entertainment System (v. 20210216-231042)
File SHA-1: 09D97003BF9D676F24A75CF3E1DCED28CDA3BE59
File CRC32: 70044A74
ROM SHA-1: 22D57AC6066529D199FCD299159D94820042C7D0
ROM CRC32: FB98D46E

File MD5: D35F9979F206897DF94FB5425E23FC85
ROM MD5: C9C94DF2EBB19BD6D717B2CFBF977574
```

## Known Issues / TODO
* Only first level fruit is strawberries
* Character bonus success animation not converted
### v2.0 targets
* Rework Madeline sprites?
* Convert polar bear character into Granny...

## Credits
* Ubvoiu: pixel art, play-testing, insight.
* hornc: hex hacking, palettes, sprites.

### Software used:
* [Nestile](https://github.com/jmcmahan/nestile) NES graphics editor.
* [GHex](https://github.com/GNOME/ghex) hex editor.
* [Lipx](https://github.com/kylon/Lipx) [IPS](https://zerosoft.zophar.net/ips.php) patch creator.

Tested and debugged using [Mednafen](https://mednafen.github.io/) multi-system emulator.

Thanks and credit to Maddy Thorson and Maddy Makes Games for Celeste and Madeline characters!

Ice Climber copyright 1984 Nintendo.
