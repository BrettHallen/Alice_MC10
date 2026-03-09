# Purpose
Simple designs for the Tandy TRS-80 MC-10 and Matra Alice.<br>

This boldly red computer is a French version of the Tandy MC-10 using the same Motorola 6803 CPU clocked at 890KHz and using the same MC6847 Video Display Generator (VDG).<br>

It was built by French companies Matra and Hachette but seems to be commonly known simply as the "Matra Alice".<br>

## YouTube Videos
- [Part 1: First Look](https://youtu.be/JoOMIVsprkE)
- [Part 2: Keyboard Problem](https://youtu.be/W2BdekgW1rA)
- [Part 3: Tandy TRS-80 MC-10 Comparison](https://youtu.be/A9SVZOl3z24)
- [Part 4: Keyboard Fixed & Internal 8KB RAM Upgrade](https://youtu.be/OvdkhOnV7no)

## RGB Video Pinout
- Pin 1 = n/c
- Pin 2 = ground
- Pin 3 = red
- Pin 4 = synch
- Pin 5 = green
- Pin 6 = audio
- Pin 7 = blue

I had to tweak variable resistor R45 in the video output stage to get a stable image.<br>

It appears to adjust the level of Field Sync. and Horizontal Sync. signals coming out of the MC6487 VDG.<br>

## [DIN-to-VGA Adapator](/DIN_To_VGA)
A simple adaptor board to take the 7-pin DIN output (via a 7-pin DIN male-to-male cable) and convert to a VGA socket & 3.5mm audio socket.<br>

## [Internal 4KB-to-8KB RAM Upgrade](/Internal_8KB_RAM)
Upgrade the Alice or MC-10 internal RAM from 4KB to 8KB.  Note that the extra 4KB isn't available if the 16KB expansion is also attached.<br>

BUT ... check out the expander below as there is a version that should work with the 8KB upgrade.<br>

## [RGB Video Modification](/RGB_Video) (Work In Progress)
Convert the MC-10 video output from RF modulated to RGB - design is based on the Matra Alice.<br>

## [Expander](https://github.com/Fred72z/ALICE)
Check out [Fred72z's](https://github.com/Fred72z) excellent expansion for Alice & MC10 ... RAM, joysticks, cartridge.
