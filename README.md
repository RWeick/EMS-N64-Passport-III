# EMS-N64-Passport-III
The full schematic, gerbers, the GAL JEDEC, and the rom for the N64 Passport III (Gameshark clone)

The deciphered logic from inside the GAL 16V8 shows that its purpose was to handle whether the cartridge delivered the game rom or the Gameshark rom to the N64 depending on what address was being read on the N64. It is unclear at this time why the GAL was even necessary for this, as there seems to still be plenty of capacity left on the Altera.

PCB Thickness: 1.2 mm

![image](https://github.com/Modman/EMS-N64-Passport-III/blob/main/Passport.png)
