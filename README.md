# FreeIntv
FreeIntv is a libretro emulation core for the Mattel Intellivision designed to be compatible with joypads from the SNES era forward even if they originally required a number pad.

## Authors

FreeIntv was created by David Richardson.

## License
The FreeIntv core is licensed under GPLv3. More information at https://github.com/markwkidd/FreeIntv/blob/master/LICENSE.

## BIOS
FreeIntv requires two Intellivision BIOS files to be placed in the libretro 'system' folder:

| Function | Filename* | MD5 Hash |
| --- | --- | --- | 
| Executive ROM | `exec.bin`  | `62e761035cb657903761800f4437b8af` |
| Graphics ROM | `grom.bin` | `0cd5946c6473e42e8e4c2137785e427f` |

* BIOS filenames are case-sensitive


## Entertainment Computer System and Intellivoice
FreeIntv does not currently support Entertainment Computer System (ECS) and Intellivoice functionality. Contributions to the source are welcome!

## Controller overlays
Mattel Intellivision games were often meant to be played with game-specific cards overlaid on the numeric keypad. These overlays convey information which can be very useful in gameplay. Images of a limited selection of Intellivision titles are available at: http://www.intellivisionlives.com/bluesky/games/instructions.shtml

## Controls

| RetroPad | FreeIntv Function |
| --- | --- |
| D-Pad| 8-way movement |
| Left Analog Stick | 16-way disc |
| A | Left Action Button |
| Y | Top Action Button |
| X | Use the Last Selected Intellivision Keypad Button (see Mini-Keypad below for more information) - In Astrosmash, for example, you can leave "3" selected to enable instant access to hyperspace. |
| L/R | Show Intellivision Mini-Keypad which allows you to view and select keys from a small Intellivision pad in the lower corner of the display. |
| Start | Pause Game |
| Select | Swap left/right controllers - Some games expect the left controller to be player one, others expect the right controller. This isn't a problem if you have two controllers (and don't mind juggling them) but users with only one controller or using a portable setup would be effectively locked out of some games. Pressing select from either controller with swap the left controller for the right and vice-versa. |

