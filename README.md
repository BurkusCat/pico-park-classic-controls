# PICO PARK:Classic Edition control configurations
![pico-header](https://user-images.githubusercontent.com/7528322/132099203-68ced1b5-5b13-43fd-bada-60e72aed0c27.jpg)

## How to use a keyboard configuration file
1. Copy a `userdata.lua` file from one of the directories (you probably want `SixPlayerKeyboardConfig`, read `CONTROLS.md` in that directory for all the controls for each player).
2. Go to your Pico Park game install location e.g.
`C:\Program Files (x86)\steamapps\steamapps\common\PICO_PARK\save`
3. Overwrite `userdata.lua` with the downloaded file (bear in mind this will wipe any hi-scores you have. Replace only the `keyboardConfig=` section with the downloaded one if you have any scores you want to keep). 

## keyboardConfig schema

Players 2+:
``` js
{
    22, // ACTION?
    88, // UNUSED
    22, // JUMP
    22, // ACTION?
    18, // DOWN
    0,  // LEFT
    3,  // RIGHT
    22, // ACTION?
    88, // UNUSED
    88, // UNUSED
},
```

## Key mappings
I didn't realise there was an in-game keyboard control editor so I spent time decoding what the IDs bound. In case it is of any use this is as far as I got:

| ID          | Key         |
| ----------- | ----------- |
| 0           | A           |
| 1           | B           |
| 2           | C           |
| 3           | D           |
| 4           | E           |
| 5           | F           |
| 6           | G           |
| 7           | H           |
| 8           | I           |
| 9           | J           |
| 10          | K           |
| 11          | L           |
| 12          | M           |
| 13          | N           |
| 14          | O           |
| 15          | P           |
| 16          | Q           |
| 17          | R           |
| 18          | S           |
| 19          | T           |
| 20          | U           |
| 21          | V           |
| 22          | W           |
| 23          | X           |
| 24          | Y           |
| 25          | Z           |
| 26          | 1           |
| 27          | 2           |
| 28          | 3           |
| 29          | 4           |
| 30          | 5           |
| 31          | 6           |
| 32          | 7           |
| 33          | 8           |
| 34          | 9           |
| 35          | 0           |
| 36          | -           |
| 37          | =           |
| 38          | SPACEBAR    |
| 39          |             |
| 40          | TAB         |
| 41          | BACKSPACE   |
| 42          | ESCAPE      |
| 43          | F1          |
| 44          | F2          |
| 45          | F3          |
| 46          | F4          |
| 47          | F5          |
| 48          | F6          |
| 49          | F7          |
| 50          | F8          |
| 51          | F9          |
| 52          | F10         |
| 53          | F11         |
| 54          | F12         |
| 55          |             |
| 56          |             |
| 57          |             |
| 58          | PAGE UP     |
| 59          | PAGE DOWN   |
| 60          |             |
| 68          | RIGHT ARROW |
| 69          | LEFT ARROW  |
| 88          | UNBOUND?    |
